
#ISSUES

* problem indexing some files as splunk thinks they are the same (need to edit input crclength / crcsalt)
* records do not contain day of month, only day of week which is not ideal for search efficiency.
* records do not always contain full timestamps - some timestamps miss certain data between yearly files in same sourcetype which causes problems.

#TODO

*add population data (by race / age) so that can work out birth rate per demographic