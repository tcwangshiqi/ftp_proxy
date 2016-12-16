# ftp_proxy
The transparent proxy firewall for ftp service control

This projects basically implement a transparent proxy firewall to capture, parse and send the tcp packet between specific inside client and outside servers.

And based on the tcp proxy, we specifically supervise the port of 21 which is the ftp connection. We could see all of the detailed commands of request and response between client and server to ensure the correct connection and data trans.
