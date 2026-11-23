# Wayne Clock

A small live countdown for embedding in Notion. It ticks every second in the Europe/London time zone (GMT in winter, BST in summer).

## Live page

https://raviolli-h.github.io/wayne-clock/?wake=7&bed=23

## What it shows

- The current time in Europe/London
- Time left today, until midnight
- Awake time left (default wake 07:00, bed 23:00)
- Time left this week (the week runs Monday 00:00 to Sunday 23:59)
- Progress through the current month and year

## Query parameters

- `wake` and `bed`: an hour such as `7` or `07:00` (defaults are 7 and 23)
- Example: `/?wake=7&bed=23`

Change the hours in the URL if the waking day changes. The page collects no personal data; everything runs in the browser.

## Licence

MIT
