---
tags:
  - 스텔라툰
last updated: 2024-01-31
---
> [[버전 네이밍 규칙]]

```dataview
TABLE WITHOUT ID
	icon as "",
	file.link as "버전",
	dateformat(last-updated, "yyyy년 MM월 dd일") as "날짜"
FROM
	"StellaTone/Version/info"
```
