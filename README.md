# Build Modern Next 14 Server Side App

### What's Client Side Architecture?


All the Client, Server architecture are based upon request, response model.

The client-server architecture refers to a system that hosts, delivers, and manages most of the resources and services that the client requests. In this model, all requests and services are delivered over a network, and it is also referred to as the networking computing model or client server network.

Client-server architecture, alternatively called a client-server model, is a network application that breaks down tasks and workloads between clients and servers that reside on the same system or are linked by a computer network.

Modern websites use a well-known concept called — Infinite Scroll. It’s the natural pattern when the user consumes in the form of infinite posts. As we can’t just render 1 million posts, the information is delivered in chunks. Once the user finishes with a chunk, they scroll down to see the next piece (page). It’s used on many platforms, like Twitter, Facebook, Pinterest and etc.



### But how does it work?

![Server Side architecture](client-server-network.webp)



The HTTP communication protocol helps establish the connection between the client and the server.
The client sends a request in the form of an XML or a JSON over the active connection. The client and server both understand the message format.
Upon receiving the client request, the server searches the requested data and sends back the relevant details as a response in the same format in which the request was received.



### React Hooks make it easy to monitor the inView state of your components when that leaves the viewport.


React implementation of the Intersection Observer API to tell you when an element enters or leaves the viewport.



```
npm install react-intersection-observer --save
```

### Framer Motion.

Production-ready declarative animations library for React.

```
npm install framer-motion
```

### OUTPUT/RESULTS --------------------------------

![Anime Website](example.png)
