1) Download portscan.py

2) Try the following example:

#---portscan example---------

from portscan import 

ip="192.168.75.150"
port=80
timeout=3

print scan(ip,port,timeout)

#---------------------------

Change the value of ip to some host you know.

Experiment to find optimal timeout in your network. Use a port you know to be closed, and if
the result is "timeout", increase the value until you get "open", "closed", or "filtered".

3) Write your own port scanning app! :)