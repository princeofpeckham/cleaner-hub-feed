# cleaner-hub-feed

Auto-generated **live schedule feed** for the Appear Here Cleaner Hub.

`feed.csv` is written by the scheduled refresh task (weekdays) and read by the hub
at runtime. It contains only **space names, addresses, postcodes, brand names and
dates** — no KeyNest codes, no personal data. Do not edit by hand; changes are
overwritten on the next refresh.

Public so the hub can fetch it from the GitHub raw URL without triggering a Netlify
rebuild on every update.
