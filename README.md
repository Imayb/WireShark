# WireShark
[gti1.png](https://postimg.cc/kRxNcZ02)

^ Using a filter to get an IP address the “192.168.0.50” is an identifier and IP is the type 

^ getting the IP with identifier and using an operator “and” to get a TCP protocol packet. Can also use other operators and different type of qualifiers like type: host, direction: src or dst and proto: TCP, UPD and others to get a specific protocol and port


Getting packets with the source and destination of ip 192.168.0.50 src allows us to capture packets from a specific host, dst is capturing packets 




proto[offset:size(optional)]=value, where proto is the desired protocol to filter, offset is the position of the value in the header, size is the length of the data you are looking for and value is the data you want to find.


Trying to get tcp SYN/ACK flag packets only they are highlighted in black and red text

^Display filter clicked a field name and it shows relation 

^ Endpoints are devices that communicate between each other in wireshark. Can click on ethernet, ipv4, ipv6, tcp, udp, each one shows different addresses, packets, bytes ect. for the packet that was selected.

^I/O graph x-axis time in seconds and y-axis represents packets per tick can filter the graph and is displaying tcp errors and filtered packets.

^Flow graph troubleshoots dropped connections, lost frames, re-transmission traffic

^ Round-trip time is the duration that the ACK for a sent packet is received. The x-axis represents the TCP sequence number, while the y-axis represents the RTT in second

^ portray unidirectional traffic, about 50000 bits after .5 seconds 

^ This graph is used to depict the flow of TCP unidirectional traffic with time the y-axis represents the TCP sequence number and the x-axis represents the time in seconds.
