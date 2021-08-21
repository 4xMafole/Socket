# Java Socket Learning
## Programs
- ## A Trivial Sequential Server
    -   `DateServer.java`
    -   `DateClient.java`

#### Description
<p> This is perhaps the simplest possible server. It listens on port 59090. When a client connects, the server sends the current datetime to the client. The connection socket is created in a try-with-resources block so it is automatically closed at the end of the block. Only after serving the datetime and closing the connection will the server go back to waiting for the next client. </p>