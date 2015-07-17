# support_ticket_sla
Track support engineers that accepted service requests with missed SLAs.

#==============================================================
# webmon_missed_sla.py - Script for checking SRs with missed SLA yanked by CSEs
# 
# Script asks user for webmon URL as input:
# For example : http://www-tac.cisco.com/cgi-bin/WebMonitorC3/Web-Mon.cgi?Site=sj&QUEUE=WW-VPN
#
# Output file is a .CSV with Parsed/Scraped Data.
#
# July 2015, amaged@cisco.com
#
#==============================================================

This tool tracks the web-based queue to find out which support engineers accepted service requests marked with a missed SLA, It creates a CSV file, copying the names of engineers that accepted SRs with Missed SLAs, the SR number and Time.
That helps in identifying the need for hiring more engineers, but it does not include collab cases.

