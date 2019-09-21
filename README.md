# Hyper Text Transfer Protocol

### These are my notes from studying the HTTP protocol in depth. Updating constantly.

The HTTP is an application-level protocol for distributed, collaborative, hyermedia information systems that is used to deliver data.

**Default port is 80**
**It provides standarized way to communicate between parties.**

## Basic features:

* HTTP is connectionless
The clien initiates a request and after it is made the client awaits for the reponse. The server processes the request and sends a response back after which the client disconnect the connection. So **client and server know about each other during current request and response only**. Further requests are made on new connection.

* HTTP is media independent
Any type of data can be sent by HTTP.

* HTTP is stateless
Neither the client nor the server can retain information between different requests.