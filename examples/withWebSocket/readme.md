## esp-fs-webserver
This example is a little bit more advanced respect to the [simpleServer](https://github.com/cotestatnt/esp-fs-webserver/tree/main/examples/simpleServer) example.

Basically is the same code, but with the adddition of a **WebSocket client** 
(I've used this library [arduinoWebSockets](https://github.com/Links2004/arduinoWebSockets), so it is needed to compile, but you can choice wich you prefer).

With the help of WebSocket technology, we can send message from server-to-clients or from client-to-server in a **full-duplex communication channels over a single TCP connection.**
In this very simple example is used only to push from ESP side a message (ESP system time) to the connected clients, just to show hot to setup a system like this.