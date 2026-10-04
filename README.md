---
license: cc-by-4.0
pretty_name: TableJourney food festival calendar
tags: [food, festivals, travel, events, calendar]
size_categories: [1K<n<10K]
---

# TableJourney food festival calendar

1,454 food festivals in 55 countries and 221 cities, each with the dates of its
next edition, from the guides at [TableJourney](https://tablejourney.com). Rebuilt from the same data as the site's
[festival calendar](https://tablejourney.com/festivals/) and [statistics](https://tablejourney.com/festivals/statistics/).
Snapshot: 2026-10-04.

## Files

- `festivals.csv` and `festivals.json`: one row per festival.

## Fields

| Field | Meaning |
|---|---|
| name | Festival name as the organiser writes it |
| city, country | Where it takes place (the TableJourney city guide it belongs to) |
| start_date, end_date | Next edition, ISO dates (the one running now, or the next to start) |
| month | Month the next edition starts |
| dates_confirmed | true when the organiser has published these dates; false when they follow the festival's usual pattern and are expected |
| recurs | yearly, or one-off or irregular |
| kinds | Theme labels, semicolon separated (wine, street food, beer, Christmas markets...) |
| focus | The cuisine or product the festival centres on, where there is one |
| free_entry | true: no ticket needed; false: ticketed; blank: not checked |
| page_url | The festival's TableJourney page: dates, what to eat, where to eat nearby |

## Scope

These are the festivals in TableJourney's guides, which follow the cities it covers
(35% are in the United States), not every food festival in the world. Closed festivals and season-long
events running longer than about two months are left out.

## Licence and credit

CC BY 4.0. Free to use, including commercially. Please credit TableJourney and link to
https://tablejourney.com/festivals/ (or the row's page_url when you use one festival). Live feeds instead of a
snapshot: [calendar feeds](https://tablejourney.com/calendar/) and [embeddable widgets](https://tablejourney.com/widgets/).
