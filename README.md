# docker-sample-ruby-2.2
Sample Hello World Ruby application serving on exported port.


## Running the Ruby app
`export PORT=8080` <br/>
`docker run -d -e "PORT=$PORT" -p $PORT:$PORT ruby-sample`
## Building Docker image locally 
`docker build -t ruby-sample .`
