## CS6200 GaTech Graduate Introduction to Operating Systems

### Multithreaded File Server

In this project, I successfully designed and implemented a multi-threaded server catering to static files, following the GetFile protocol. This protocol resembles a straightforward HTTP-like system. Additionally, a multi-threaded client, functioning as a load generator for the server, was created. Both the server and client were crafted in C, adhering to a robust and scalable design.

### Inter-Process Communication

Building upon the foundation laid in Project 1, I completed the augmentation of a functional getfile server in two parts:

- Part 1: The getfile server was transformed into a proxy server. This proxy server accepts incoming GETFILE requests and translates them into HTTP requests for another server, possibly situated on the internet.

- Part 2: A simple cache server was implemented, communicating with the proxy through shared memory. The design of this cache server enables its utilization with multiple proxy servers.


### gRPC and Distributed File System

For this project, I successfully designed and implemented a straightforward distributed file system (DFS). The initial phase involved developing file transfer protocols using gRPC and Protocol Buffers. Subsequently, a weakly consistent synchronization system was incorporated to manage cache consistency between multiple clients and a single server. The system demonstrated capability in handling both binary and text-based files.

The source code for these tasks was executed using a combination of C++14, gRPC, and Protocol Buffers, resulting in a comprehensive implementation.