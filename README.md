# tcpgrep
A command line tool that greps TCP attributes from PCAP file.

Developed a command line application called “tcpgrep” which takes a PCAP file as input and greps/searches for various TCP parameters as mentioned below:

tcpgrep 

-t Display total number of TCP sessions.

-i Display total number of incomplete TCP sessions.

-in Display total number of incomplete TCP sessions with packet numbers.

-r Display total number of RST packets.

-rn Display total number of RST packets with packet numbers.

-a Display total number of duplicate TCP ack packets.

-an Display total number of duplicate TCP ack packets with packet numbers.

-p <num1> - <num2> Dump specific range of TCP packets. Dump one by one if no range is specified from first.

-p <IP:port> Start dumping packets with specified IP port.

-p <TCP Flag> Start dumping packets with specified TCP Flag.
(U: Urgent,A: Acknowledgement,P: Push,R: Reset,S: Sync,F: Fin)




