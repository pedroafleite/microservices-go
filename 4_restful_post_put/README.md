# Test it!


### Run it on the server side:

`go run main.go`

Then `ctrl+c` to see graceful shutdown message.


### Run it on the client side:

`curl -v localhost:9090` GET

`curl -v localhost:9090 -d '{"name": "tea", "description": "a nice cup of tea"}'` POST

`curl -v localhost:9090/3 -XPUT -d '{"name": "tea", "description": "an edited cup of tea"}'` PUT

