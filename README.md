# websocket

Build Web Chat Server based on websocket

### Prerequisite

You need to have:

* Go 1.8
* Go Environment properly set
* Bzr Utils

### Compilation


```sh
git clone https://github.com/jsenon/websocket.git
cd pkg
go get github.com/stretchr/gomniauth
go get github.com/stretchr/gomniauth/providers/google
go get github.com/stretchr/objx
go get github.com/gorilla/websocket
go get github.com/clbanning/x2j
go get github.com/ugorji/go/codec
go get labix.org/v2/mgo/bson
cd ../src  
go build -o chat
```

### Start

```sh
./chat -addr=YOURIP:YOURPORT ie. -addr=127.0.0.1:8090
```

### Access

Access through favorite web browser on http://YOURIP:YOURPORT ie http://127.0.0.1:8090

### ToDo





