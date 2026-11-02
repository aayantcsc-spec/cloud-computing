Cloud Computing Practical Journal - Source Code
M.Sc. IT Part I, Semester I (University of Mumbai)
Submitted by: Shruti Gupta | Roll No: 264450

Compile: javac *.java   (inside each folder)
Run server first, then client, in separate terminals.

P1A_TCP_Prime        tcpServerPrime (port 8001), tcpClientPrime
P1B_TCP_Chat         ChatServer (port 8000), ChatClient  (type STOP to end)
P2A_UDP_EvenOdd      udpServerEO (port 2000), udpClientEO (port 1000)
P2B_UDP_Calculator   RPCServer (port 1200), RPCClient (port 1300); input e.g. "add 3 4", "q" quits
P3_Multicast         BroadcastServer, BroadcastClient (group 239.1.2.3, port 1234)
P4_RMI_DateTime      javac *.java; start "rmiregistry" in that folder (or use
                     "start rmiregistry"), then run ServerDate, then ClientDate.
                     On Java 9+ rmic is not needed (dynamic stubs).
