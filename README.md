# websocket

Build CLI Chat Server based on redis

### Prerequisite

You need to have:

* Go 1.8
* Go Environment properly set
* Redis Docker image

### Compilation

Start your redis

```sh
git clone https://github.com/jsenon/websocket.git
go get github.com/stretchr/gomniauth
go get github.com/stretchr/gomniauth/providers/google
go get github.com/stretchr/objx
go get github.com/gorilla/websocket
cd src  
go build -o chat
```

### Start

```sh
./chat -addr=YOURIP:YOURPORT ie. -addr=127.0.0.1:8090
```

### Access

Access through favorite web browser on http://YOURIP:YOURPORT ie http://127.0.0.1:8090

### ToDo





