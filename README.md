# check_mysqldump-secure
Nagios Plugin to monitor mysqldump database backups


Nagios Plugin to monitor the state of mysql database dumps. The following states are reported:
* Did every database dump correctly?
* Is the last dump within the specified time cycle?
* If encryption is required, was the dump encryted?
* If compression is required, was the dump compressed?
* If logging is required, was the dump logged?
 
Additional information is displayed. Such as:
* How many databases dumped
* How many databases skipped
* How long did it take to dump everything
* How many megabytes have been dumped

It is planned to included dumping time and size into performance data, so you have a nice overview of when and how those two values have increased.
