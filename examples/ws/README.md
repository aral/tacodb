## connect to tacodb/level over websockets

Create a streaming connection with websockets!

### server with websockets & multilevel:

``` js
//examples/ws/server.js

{{{!cat ./server.js}}}
```

### brower/node client with websockets

``` js
//examples/ws/client.js

{{{!cat ./client.js}}}
```

this client can be used from both the browser and node.js!

### running the server & client

start the server
``` sh
tacodb local server.js --name ws
```

connect from node:

``` sh
node client.js
```

or from the [browser](http://localhost:8000/)


