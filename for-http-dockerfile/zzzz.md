
``` sh

docker build -f Dockerfile -t for-http-dockerfile:0.1 .



docker ps


docker run -p 8080:8080 for-http-dockerfile:0.1
#docker run -d -p 8080:8080 for-http-dockerfile:0.1

```

