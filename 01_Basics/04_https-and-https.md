# Introduction to HTTP and HTTPS

## HTTP

HTTP (Hypertext Transfer Protocol) is an application layer protocol that is used to collect and transfer data (audio, video, images, etc) over the World Wide Web. It follows client-server model (protocol) that works on the top of TCP/IP protocol and uses request-response protocol.

### Working

In HTTP, when the client sends a request message to the server, HTTP will create a connection (TCP connection) between the client and the server. The HTTP works as a transmission protocol for the client and the server to communicate with each other. Once the server sends the data or the response to the client, the TCP connection will be terminated. If the client again sends the new request to the server, a new TCP connection is created. **HTTP uses port number 80**

### Features

- **HTTP is media-independent:** Any format of data can be shared over the HTTP with no issues if both the client and server understand how to process the data.
- **HTTP is connectionless:** After serving a single HTTP request, the client-server connection is closed and that same connection is never used again.
- **HTTP is stateless:** The client and server only know about each other during the current request, and when the connection is disconnected, both the client and the server forget about each other.

## HTTPS

HTTPS (Hypertext Transfer Protocol Secure) is a better version of HTTP, where the data is shared over the network (world wide web) securely. HTTPS shares the data over the network in the encrypted format, such that no third-party can read and access the data. To encrypt communications HTTPS uses an encryption protocol called **Transport Layer Security (TLS)**, formerly known as [Secure Sockets Layer (SSL)](https://www.cloudflare.com/learning/ssl/what-is-ssl/). HTTPS protocol uses the 443 port number for communicating the data.