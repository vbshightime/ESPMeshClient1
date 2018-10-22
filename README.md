# ESPMeshClient1
##  Mesh Network
A mesh network (or simply Meshnet) is a local network topology in which the infrastructure nodes (i.e. bridges, switches and other infrastructure devices) connect directly, dynamically and non-hierarchically to as many other nodes as possible and cooperate with one another to efficiently route data from/to clients.
Mesh networks dynamically self-organize and self-configurable. Mesh networks can relay messages using either a flooding technique or a routing technique. With routing, the message is propagated along a path by hopping from node to node until it reaches its destination.

## Introduction
We have created a Mesh network or a star network. Our architecture consists of two cientsand one server. Clients or nodes continuously braodcast
the temperature and humidity values to the differnt nodes in the network. Values relayed by clients are fetched by server. The server parse
these values and post it to cloud. We are making use of [painlessMesh]() library. This library provide us easy and user friendly ways to create a mesh network.
There are different ways by which we can creat a energy efficient and reliable mesh nework. This library uses different other libraries like [TaskScheduler](),
[Arduino Json](), [AsyncWebServer]() and [AsyncESP]() to serve this operation. 
