---
name: 吴沛豪
gender: 男
birthday: 2000-10-12
email: wupeihao@njmu.edu.cn
phone: 15151056689
tags: family closerfamily
---

## 基本资料

姓名：`=(this.name)`
年龄：`$= let date = moment(dv.current().birthday.toString(),"yyyy-MM-DD"); let today = moment().startOf('day'); today.diff(date,"years")`岁
邮箱：`=(this.email)`
手机：`=(this.phone)`

## 习惯追踪

```dataview
TABLE WITHOUT ID
	link(file.name) as "日期",
	摘录 AS "🌄",
	运动 AS "🏃‍♂️",
	邮件 AS "💌",
	写作 AS "📝",
	心情 AS "👾",
	总结
	FROM "00 - 每日日记/DailyNote" 
	SORT file.name DESC
	LIMIT 7
```

## 本周任务
```tasks

```