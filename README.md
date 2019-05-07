# sysinternals
Configuration files for sysinternals software

### SYSMON ###

System Monitor (Sysmon) is a Windows system service and device driver that, once installed on a system, remains resident across system reboots to monitor and log system activity to the Windows event log.
~~~~
sysmon.exe -accepteula -i C:\Windows\sysmon-server.xml
sysmon.exe -accepteula -i C:\Windows\sysmon-client.xml
~~~~

SOURCE

https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon
