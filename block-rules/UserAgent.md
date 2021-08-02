# User Agents

No external software should be allowed to interact with your website. Thus blocked.

### Use the following expression to block such user agents:

```
(http.user_agent eq "")
or (http.user_agent eq "unknown")
or (http.user_agent eq "undefined")
or (http.user_agent eq "Empty user agent")
or (http.user_agent contains "HTTrack")
or (http.user_agent contains "bxss")
or (http.user_agent contains "nmap")
or (http.user_agent contains "masscan")
```
