# ftp_proxy
The transparent proxy firewall for ftp service control

This projects basically implement a transparent proxy firewall to capture, parse and send the tcp packet between specific inside client and outside servers.

And based on the tcp proxy, we specifically supervise the port of 21 which is the ftp connection. We could see all of the detailed commands of request and response between client and server to ensure the correct connection and data trans. For example the firewall could parse the command and information like username, passwd, current directory, and etc.
![]({{site.baseurl}}/https://github.com/tcwangshiqi/ftp_proxy/blob/master/Screenshot%20from%202016-12-13%2001%5E%2539%5E%2540.png?raw=true)
