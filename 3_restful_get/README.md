# Test it!


### Run it on the server side:

`go run main.go`

Then `ctrl+c` to see graceful shutdown message.


### Run it on the client side:

`curl -v localhost:9090` to retrieve JSON.

`curl -v localhost:9090 -XDELETE -v` to see that the method is not allowed.

