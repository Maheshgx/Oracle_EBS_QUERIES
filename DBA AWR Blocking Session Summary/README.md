# [DBA AWR Blocking Session Summary](https://www.enginatics.com/reports/dba-awr-blocking-session-summary/)
## Description: 
Summary of blocked and blocking sessions based on the active session history from the AWR.
The link to blocking sessions is deliberately nonunique without jointing to sample_id to increase the chance to fetch the blocking session's additional information such as module, action and client_id.
In some cases, such as row lock scenarios, the blocking session is idle and does not show up in the ASH.

We recommend doing further analysis with a pivot in Excel rather than by SQL, as Excel's drag- and drop is a lot faster than typing commands manually.
## Categories: 
[DBA](https://www.enginatics.com/library/?pg=1&category[]=DBA), [Diagnostic Pack](https://www.enginatics.com/library/?pg=1&category[]=Diagnostic+Pack), [Enginatics](https://www.enginatics.com/library/?pg=1&category[]=Enginatics)
## Dependencies
If you would like to try one of these SQLs without having Blitz Report installed, note that some of the reports require functions from utility package [xxen_util](https://www.enginatics.com/xxen_util/true).
# Report Example
[DBA_AWR_Blocking_Session_Summary 21-Jan-2019 095329.xlsx](https://www.enginatics.com/example/dba-awr-blocking-session-summary/)
# [Blitz Report™](https://www.enginatics.com/blitz-report/) import options
[rep_DBA_AWR_Blocking_Session_Summary.sql](https://www.enginatics.com/export/dba-awr-blocking-session-summary/)\
[rep_DBA_AWR_Blocking_Session_Summary.xml](https://www.enginatics.com/xml/dba-awr-blocking-session-summary/)
# Oracle E-Business Suite reports

This is a part of extensive [library](https://www.enginatics.com/library/) of SQL scripts for [Blitz Report™](https://www.enginatics.com/blitz-report/), which is the fastest reporting solution for Oracle EBS. Blitz Report is based on Oracle Forms so is fully integrated with E-Business Suite. 

![Running Blitz Report](https://www.enginatics.com/wp-content/uploads/2018/01/Running-blitz-report.png) 

You can [download](https://www.enginatics.com/download/) Blitz Report and use it [free](https://www.enginatics.com/pricing/) for up to 30 reports. 

Blitz Report runs as a background concurrent process and generates output files in XLSX or CSV format, which are automatically downloaded and opened in Excel. Check [installation](https://www.enginatics.com/installation-guide/) and [user](https://www.enginatics.com/user-guide/) guides for more details.

If you are interested in Oracle EBS reporting you can visit [www.enginatics.com](https://www.enginatics.com/), check our [blog](https://www.enginatics.com/blog/) and try to run this and other reports on our [demo environment](http://demo.enginatics.com/).

© 2020 Enginatics