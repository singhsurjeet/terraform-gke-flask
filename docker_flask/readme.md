## Build Hello world python docker image

`docker build -t docker_flask:latest .`

## If running locally

`docker run -d -p 5000:5000 docker_flask:latest`

### Access via browser or curl 

```
$ curl http://127.0.0.1:5000/
{
"hello": "world"
}
```
