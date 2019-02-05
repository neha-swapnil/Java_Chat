# Java_Chat
A group chat project done using simple socket programming using java MulticastSocket class.

A MulticastSocket is a (UDP) DatagramSocket, with additional capabilities for joining “groups” of other multicast hosts on the internet.

Simply writing the code and save the file as GroupChat.java and compile it using javac and then run the program using two command line arguments as specified. A multicast host is specified by a class D IP address and by a standard UDP port number. Class D IP addresses are in the range 224.0.0.0 to 239.255.255.255, inclusive. The address 224.0.0.0 is reserved and should not be used.

Compile:-

javac GroupChat.java

Run terminal/cmd 1:-

java GroupChat 239.0.0.0 1234

Run terminal/cmd 2:-

java GroupChat 239.0.0.0 1234

To quit the program:-
Exit//type on both the terminals/cmds one at a time.


OUTPUTS:--
CMD1/TERMINAL1
javac GroupChat.java 
java GroupChat 239.0.0.0 1234
Enter your name: Neha
Start typing messages...

Hi!
Harsh: hello!
Harsh: sup?
you ood?
good?*
I'm fine!
Exit
Socket closed!


CMS2/TERMINAL2
java GroupChat 239.0.0.0 1234
Enter your name: Harsh
Start typing messages...

Neha: Hi!
hello!
sup?
Neha: you ood?
Neha: good?*
Neha: I'm fine!
Exit
Socket closed!



-----------------------------------*******************---------------------------*******************-----------------------------
