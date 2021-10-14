# Implementation-of-Distributed-System
AOS CS6378 - Instructor Neeraj Mittal - Fall 2021

CS 6378 - Project 1
Team Members
1. Shashank Sathish 
2. Sharanya Sathish
3. Preetika Lakshmanan

System Design,
Created the neighboring socket connections, after parsing the file. The parsed data was stored as a java object called NodeInfo. In turn these were an object of a class called hostsPorts that stored all the information about the Host Id, node Id, and the Host Name. Since multiple requests are received by the server, we have provided with a multithreaded client handler that handles the communication part. Since our implementation communicates with one client at a time, we had implemented a Queue to store all the incoming message.

How to execute,
The project can be complied on the dc machines using javac *.java command. After that, the nodes mentioned on the config.txt file must be ssh(ed) and run the following command, java Main <nodeNumber> <configFile Location>.
  
Result
The code yielded a correct result for the sample config file that was provided. Besides, when we tried tweaking the config.txt file to verify other possible conditions, we received a correct output. 


