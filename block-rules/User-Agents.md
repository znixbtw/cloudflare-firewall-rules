# User Agents

### Use the following expression to Block:

```
(http.user_agent eq "")
or (http.user_agent eq "unknown")
or (http.user_agent eq "undefined")
or (http.user_agent eq "Empty user agent")
or (http.user_agent contains "HTTrack")
or (http.user_agent contains "bxss")
or (http.user_agent contains "nmap")
or (http.user_agent contains "masscan")
or (http.user_agent contains "python")
or (http.user_agent contains "Go-http")
or (http.user_agent contains "curl")
```
