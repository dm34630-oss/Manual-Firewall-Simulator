# Manual-Firewall-Simulator
A Manual Firewall Simulator made to teach people who are new to networking and Cybersecurity how internal firewalls work.

# How to Use
This simulator is just a demonstration on how the inner workings of a firewall would block or allow certain connections.

In the first window, The Action "Deny" or "Allow" will determine whether or not the connection packet will be accepted by the network. 

Then you will insert a Source, which can be either an Internet Protocol (IP) or a Classless Inter-Domain Routing number (CIDR).

You will then insert which Destination port the connection packet will go to, you can insert any port number or just * for any port, basically the default option.

Then you will select a communication protocol. 
Transmission Control Protocol (TCP) - Meant to send HTTP/HTTPS, file transfers, and email
User Datagram Protocol (UDP) -  Meant to control real time applications, such as live video streaming, voice over IP, and online games.
Internet Control Message Protocol (ICMP) - Meant to check if a destination host is reachable; reporting network issues.

You can then write a comment relating to the packet you were planning to send.
Once you send the packets, you will notice that it gets added onto the rules. Make sure to keep the rule in mind.

Then move onto the second window, labeled "Simulator & Logs", place in the same Action, Destination Port, and Protocol, and you may add an optional note if you feel the need. Click the "Send Packets" button, and you will see that your packet was either confirmed nor denied, based on what you selected the Action as.
