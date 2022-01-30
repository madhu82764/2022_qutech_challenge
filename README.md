Our project is based on the implementation of the  Ekert protocol. It includes the code for the authentication of the interface for communication between the users Alice and Bob for sending messages, and the shared key between them.
Alice and Bob choose a basis randomly. Alice then encodes each bit of message onto a string of qubits using the basis she chose, and she sends the encoded message to Bob. Bob measures the message using his selected basis.
Alice and Bob share the bases they use over the interface, and the code calculates the common gates used in Alice and Bob's bases to form the shared key between them. 

The Ekert protocol is an entanglement-based protocol that uses maximally entangled Bell states emitted by a common source and distributed between Alice and Bob. If third person Eve interacts with the state shared between Alice and Bob, it will not remain maximally entangled anymore, and Alice and Bob can check how much Eve has interacted with the state. We have implemented the algorithm using Qiskit integrated with Quantum Inspire platform. The communication channel between Alice and Bob has been establied via twitter using tweetypy python module.

Team Experience: 
The MIT iQuHACK 2022 has been an incredible experience. 
Our team was assigned the QuTech Division, and we worked on the Quantum Key Distribution Challenge. We read about QKD and the algorithms in QKD that we could implement. We implemented the Ekert Protocol using the Quantum inspire platform and used Tweepy as the channel for sending messages. 
We gained abundant knowledge, worked together and formed good bonds with each other as a team as we sailed through the challenge. We helped each other whenever we got stuck and we would like to specially thank our mentor Tumi for his invaluable suggestions and clarifications of our doubts throughout the event. We are thankful to the entire orgranizing team for such a great arrangement. Inspite of the entirely virtual program, we were never left out from great networking and interacting with each other.




References:

1)https://www.cse.wustl.edu/~jain/cse571-07/ftp/quantum/

2)https://qiskit.org/textbook/ch-algorithms/quantum-key-distribution.html
