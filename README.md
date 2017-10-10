################# Simple Messenger ################

### Concept: 
A very simple messenger which maintains communications between 2 devices implemented using Android AVDs.

### Implementation:
* The application is launched on 2 different AVDs each with a specified port.
* Each application has a server port which is constantly active to receive messages and a client which sends messages to the other AVD.
* Messages are sent over the devices using TCP protocol.
* The Client and Server ports are implemented using Java Sockets and Java AsycTasks.
* The received and sent messages are displayed on the screen of AVD.

### Link to the Code files:
https://github.com/Sumedh0192/Distributed-Systems/blob/master/SimpleMessenger/app/src/main/java/edu/buffalo/cse/cse486586/simplemessenger/

### Link to official project description:
https://github.com/Sumedh0192/Distributed-Systems/blob/master/SimpleMessenger/PA%201%20Specification.pdf
