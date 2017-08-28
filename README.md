# chat_app
This is a python chat application that can be run on 1..n client computers on the same network.

## Usage

### Server

The server must be running before clients can be connected to it. It has an optional
argument for specifying the port to run on. The default is `6789`. To start the server:
```
./server.py [port]
```

### Client

The client can be run on any computer that has the ability to run python scripts. It
Must be on the same network as the server. It takes two arguments. The first is the
address of the server (the server should print out the address when running). The
second is the port. To start a client:
```
./client.py <address> [port]
```
