# docker-sample-ruby-2.2
Sample Hello World Ruby application serving on exported port.


## Running the Ruby app
To simply run the sample ruby application on your desired port, for example below is using 8080. Use the following commands: <br/>
`export PORT=8080` <br/>
`docker run -d -e "PORT=$PORT" -p $PORT:$PORT osodevops/docker-sample-ruby-2.2`
## Building Docker image locally 
If you need to customise the image you can build it locally using the following: <br/>
`docker build -t ruby-sample .`
