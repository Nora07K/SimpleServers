# Simple Servers

## Server Intitalization:

- To start the server on the 2000 port:
`ncat -l 2000 --keep-open -c ./EchoServer`

- To find the terminals IP ADDRESS your running the server on:
`ip a` and the adress that comes up under eth0 and inet is the ip address

## Clients Connection

- To connect to the server from a linux terminal:
`nc <ip address of the server> 2000`

- To connect to the server from windowns CLI:
`telnet <ip address> <port number>`

