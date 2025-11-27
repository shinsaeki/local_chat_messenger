# local_chat_messenger
A playground repository for experimenting with **inter-process communication (IPC)** using  
**TCP**, **UDP**, and **UNIX domain sockets** on a local machine.

This project provides simple client–server programs that exchange messages locally,  
allowing you to understand how different IPC mechanisms work in practice.

## Features
- TCP client and server example
- UDP client and server example
- UNIX domain socket (stream) communication
- Named pipe (FIFO) based message exchange
- Clean and simple Python code for experimentation
- Focused on understanding real IPC behavior

## Project Structure
```
local_chat_messenger/
│
├── tcp/
│   ├── tcp_server.py
│   └── tcp_client.py
│
├── udp/
│   ├── udp_server.py
│   └── udp_client.py
│
├── unix_socket/
│   ├── server.py
│   └── client.py
│
├── fifo/
│   ├── server.py
│   └── client.py
│
└── README.md
```
