# Project1
Project 2 (R)
For this project, think of yourself as a developer on a corporate business intelligence team. You have been given a flat file (CSV format) of login information from Maximo, an asset tracking system the company relies on. Current licensing requires that no more than 95 users in the AUTHORIZED and/or LIMITED groups be online at any given time. The deliverables outlined in this project will be submitted to the IT director, who wants to be sure that the licensing threshold is not exceeded.

The Data
The data is included in this project. The filename is Project2Data.csv.

Field	Description
attemptdate	Date and Time of event
attemptresult	LOGIN, LOGOUT, TIMEOUT, or SYSLOGOUT
userid	The user triggering the event
type	User type, i.e., AUTHORIZED
maxsessionuid	Unique identifer for a session. This will show up from LOGIN to LOGOUT, TIMEOUT, or SYSLOGOUT.
