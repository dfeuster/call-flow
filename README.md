Use cases for mvp:

- User should be able to use the application in a web browser
- User should have a welcome screen that provides the option to submit a report, agent's report review, and supervisor's report review
- User should be able to submit a report for an agent based on AD(Active Directory), that includes the date and time of the report being entered
- Submit report form should include check boxes for yes or N/A on meeting call flow requirements

Specific pieces for mvp
- agent reports
-- search by name
-- from:to date with calendar picker
- sup reports
-- search by name
-- from:to date with calendar picker
- submit report
-- input name
-- input date of report
-- check boxes for yes and n/a
-- consider checks on left and notes on right with submit
-- on submit pull up notes that can be cut and pasted if necessary(mvp)

Determine application stack for mvp
- http(part of node)
- node.js
- angular or react?
- database mysql(master, slave) or mongodb
