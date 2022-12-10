# forexfactory_news_scraper_py
ForexFactory News/Calendar Scraper In Python

Ex:
`
{'Currency': 'All', 'Event': 'OPEC-JMMC Meetings', 'Time_Eastern': '\nAll Day', 'Impact': 'Medium', 'Actual': '', 'Forecast': '', 'Previous': ''}
{'Currency': 'AUD', 'Event': 'AIG Construction Index', 'Time_Eastern': '\n4:30pm', 'Impact': 'Low', 'Actual': '48.2', 'Forecast': '', 'Previous': '43.3'}
`

## How to use
1. Make sure to have Python 3 installed
2. Run `python forexfactory_news_scraper.py`

## Notes
1. In order to customize date range, change line 106 `calendar.php?day=nov18.2016%22`.
2. The current code only prints (outputs) the events. If you want to save the events to file, add additional code to save.