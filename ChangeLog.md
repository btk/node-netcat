2013.12.30, Version 1.0.0

* TCP client, receive and send messages (Netcat.client)
* TCP server, listen on arbitary TCP ports and response to the received messages (Netcat.server)
* PortScan (Netcat.portscan)
* only deal with IPv4 and TCP


2013.12.30, Version 1.0.1

* Server - event "data" add new param "client" to identify who the sender


2013.12.30, Version 1.0.2

* Server - implement encoding
* Client - implement encoding


2013.12.31, Version 1.0.3

* Server - method 'send', when a client close connection and the server is write to socket at the moment throws a exception.