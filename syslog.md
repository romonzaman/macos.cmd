#nano /etc/syslog.conf
```
local0.*	/var/log/kamailio.log
```


```
launchctl unload /System/Library/LaunchDaemons/com.apple.syslogd.plist && launchctl load /System/Library/LaunchDaemons/com.apple.syslogd.plist
```
 

