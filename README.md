# Sysmon
System Monitor (Sysmon) is a Windows system service and device driver that, once installed on a system, remains resident across system reboots to monitor and log system activity to the Windows event log.

Original and download Link: https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon

**Usage**

Common usage featuring simple command-line options to install and uninstall Sysmon, as well as to check and modify its configuration:

Install: sysmon64 -i [<configfile>]

Update configuration: sysmon64 -c [<configfile>]

Install event manifest: sysmon64 -m

Print schema: sysmon64 -s

Uninstall: sysmon64 -u [force]
