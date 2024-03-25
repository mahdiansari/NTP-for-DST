# NTP server with timezone and DST adjustement
This time-server can adjust the time provided to the client according to their preference and the custom daylight saving time settings. It is used for all equipment that does not have the ability to disable DST.
I wrote my own version that accepts a UTC offset(timezone) and adjusts for DST. The code is below.

# Notice:
NTP does not have a because NTP is based on UTC which does not have a daylight savings time period, a switchover is not necessary inside the NTP system. The operation systems of servers and clients are solely responsible for switching from/to DST

# My code

