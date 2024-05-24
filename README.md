# linkedin-analytics-to-sqlite

Parse the LinkedIn analytics exports into a Sqlite DB.

There's not a great API for getting analytics on a personal account on LinkedIn.
There is, however, an ability to download an Excel spreadsheet of your
post statistics from the [Content Analytics Page](https://www.linkedin.com/analytics/creator/content/).

## Install

```console
me@home:~$ pip install linkedin-analytics-to-sqlite
```

## Usage

```console
me@home:~$ linkedin-analytics-to-sqlite process Content_StartDate_EndDate_ProfileName.xlsx
me@home:~$ datasette serve linkedin_analytics.db
```

