# React + Vite

What is WebSocket?
WebSocket is a communication protocol that provides full-duplex (two-way) communication channels over a single, long-lived connection between a client and a server. It is designed to work over the same ports as HTTP (80 for non-secure and 443 for secure), making it compatible with existing network infrastructure.

WebSocket enables real-time, bidirectional communication.
Once a WebSocket connection is established, the server and client can send messages to each other at any time, unlike traditional HTTP requests.
WebSocket was standardized by the IETF as RFC 6455 and is supported by most modern web browsers.

In summary, Zustand's state merge automatically means that when you update part of the state, it merges the new data with the old state rather than replacing the entire state object. This simplifies state management, especially for large or nested state objects.