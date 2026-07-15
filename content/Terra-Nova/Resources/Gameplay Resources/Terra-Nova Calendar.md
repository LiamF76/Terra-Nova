---
publish: true
title: Terra-Nova Calendar
aliases:
  - Calendar
  - Seasons
  - Days
  - Months
  - Years
---

Terra-Nova has a strict and easy to understand calendar alongside its seasons. Here is a quick breakdown:

400 days a year -> 4 months a year -> 100 days per month -> 1 season per month.

| **Month** | **Rainfall** | **Sunfall** | **Leafall** | **Snowfall** |
| --------- | ------------ | ----------- | ----------- | ------------ |
| *Season*    | *Spring*       | *Summer*      | *Autumn*      | *Winter*       |



```js
const calendarAPI = Calendarium.getAPI("Terra-Nova Prime Calendar");`
const currentDate = calendarAPI.getCurrentDate(); // this is an object { year: number, month: number, day: number }
```
