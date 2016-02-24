# LinkItOneSyncNtp
Add set system time ability to WiFiUdpNtpClient Example.
epoch to calendar time use time library by Michael Margolis, you could find it here http://www.pjrc.com/teensy/td_libs_Time.html

WARNING
LinkIt One RTC return unsign int, but time library breakTime() use long int, don't know if there is any side effect. Only tested this using current time, 2016/2/24.
