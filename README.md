# WireShark
[![gti1.png](https://i.postimg.cc/3NqLKQ9F/gti1.png)](https://postimg.cc/kRxNcZ02)

^ Using a filter to get an IP address the “192.168.0.50” is an identifier and IP is the type 

[![git.png](https://i.postimg.cc/qRFJdzfb/git.png)](https://postimg.cc/zbnZCDGK)

^ getting the IP with identifier and using an operator “and” to get a TCP protocol packet. Can also use other operators and different type of qualifiers like type: host, direction: src or dst and proto: TCP, UPD and others to get a specific protocol and port

[![git.png](https://i.postimg.cc/MGPMvZ2R/git.png)](https://postimg.cc/hJmPYBGP)

^ Getting packets with the source and destination of ip 192.168.0.50 src allows us to capture packets from a specific host, dst is capturing packets 


proto[offset:size(optional)]=value, where proto is the desired protocol to filter, offset is the position of the value in the header, size is the length of the data you are looking for and value is the data you want to find.

[![git.png](https://i.postimg.cc/3NMwvdLy/git.png)](https://postimg.cc/cgmZq4GZ)

^ Trying to get tcp SYN/ACK flag packets only they are highlighted in black and red text
[![git.png](https://i.postimg.cc/K8c8BX55/git.png)](https://postimg.cc/nC5xfPgs)

^Display filter clicked a field name and it shows relation 
[![git.png](https://i.postimg.cc/v8XjTpcy/git.png)](https://postimg.cc/c6gT5kRk)

^ Endpoints are devices that communicate between each other in wireshark. Can click on ethernet, ipv4, ipv6, tcp, udp, each one shows different addresses, packets, bytes ect. for the packet that was selected.
[![git.png](https://i.postimg.cc/rwRNRC6V/git.png)](https://postimg.cc/xXYzWmTh)

^I/O graph x-axis time in seconds and y-axis represents packets per tick can filter the graph and is displaying tcp errors and filtered packets.
[![git.png](https://i.postimg.cc/2jJqLpCW/git.png)](https://postimg.cc/6Tr6Fm26)

^Flow graph troubleshoots dropped connections, lost frames, re-transmission traffic

[![git.png](https://i.postimg.cc/SKyjbkfB/git.png)](https://postimg.cc/BjVJxWyp)

^ Round-trip time is the duration that the ACK for a sent packet is received. The x-axis represents the TCP sequence number, while the y-axis represents the RTT in seconds

[![git.png](https://i.postimg.cc/YCxYWXnw/git.png)](https://postimg.cc/XrprMg62)

^ Portrays unidirectional traffic, about 50000 bits after .5 seconds 
[![git.png](https://i.postimg.cc/P5KvxCJX/git.png)](https://postimg.cc/5XY2KN8T)

^ This graph is used to depict the flow of TCP unidirectional traffic with time the y-axis represents the TCP sequence number and the x-axis represents the time in seconds.
