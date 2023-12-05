# SCG OSS k8s
A basic OSS Spring Cloud Gateway to be used in a container

## Build container

```sh
pack build scg-oss-k8s --builder paketobuildpacks/builder:base 
```

## Run container

```sh
docker run -p 8080:8080 -p 8090:8090 scg-oss-k8s 
```
