# Banner Dataset (Fall 2014 - Spring 2019)

This folder contains this file and a large number of subfolders:

- `AcademicCalendars` and `Catalogs` folders contain printable PDF files that cover the years 2014-2019. You will also find a couple of CSV files in the `Catalogs` folder that you will need to import into your database.
- The rest of the folders (`Fall2014`, `Winter2015`,`Spring2015`, etc.) contain course offering data for every academic term since Fall 2014. Each folder contains:    
    - `banner.html`: a dump of the data scraped from Banner Web
    - `cal_rules.yaml`: configuration rules that account for holidays, schedule shifts, etc. (Note: YAML is actually a standard! Look it up.)
    - `course_meetings.csv`: a CSV-formatted table of class meetings, one line per meeting
    - `course_offerings.json`: a JSON-formatted extract all data extracted from the banner.html file; this is used to generate the final CSV files
    - `courses.csv`: a CSV-formatted table of course data
    - `Calendars`: a folder of ical files, one per course (CRN) that can be directly imported into any standard calendaring software; it has been tested with Outlook (Exchange), Mac Calendar (iCloud), and Google Calendar
    
You may use whatever files you like for your final project. However, here is a sufficient set that meet the project requirements:
- the `courses.csv` and `course_meetings.csv` for each academic term. 
- if your analytical questions involve prerequisites, program requirements, etc. then you should also use the `CourseCatalog2018_2019.csv` file. 

**Assume the files may have errors in them. Thus be sure to validate what you can in your code.**