# Chat

Simple TCP chat built with Go

## Quick Start

### Using `Go install`

```console
$ go install github.com/colaxdev/chat@latest
```

### From binary package

Go to `Releases`

## Commands

- `/nick <name>` - get a name, otherwise user will stay anonymous.
- `/join <name>` - join a room, if room doesn't exist, the new room will be created. User can be only in one room at the same time.
- `/rooms` - show list of available rooms to join.
- `/msg <msg>` - broadcast message to everyone in a room.
- `/quit` - disconnects from the chat server.
