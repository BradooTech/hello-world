# Simple http 'hello world' for load balancer testing

This image is a simple 'Hello world' in an HTTP server used to test load balancers. When receive an request (GET /) this image will return the current machine hostname.

It shows ```Hello from <hostname>``` for every request, making it easier to determine what host received the request.

## Running a simple test
    docker run --rm -it -p 80:80 helloworld-http

Will result in a single instance running on your port 80, you can test and will get a result like it:
    
![Print](/print1.png)


