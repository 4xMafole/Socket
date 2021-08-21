## **Simple Threaded Server**
<p>

*Sequential Server:* it did not read any data from the client, and worse, it served only **one client at a time.**

This next server receives lines of text from a client and sends back the lines uppercased. It **efficiently handles multiple clients at once:** When a client connects, the server spawns a thread, dedicated to just that client, to read, uppercase, and reply. The server can listen for and serve other clients at the same time, so we have true concurrency.
</p>