# tpfinal-cloud

## Quickstart

```
docker build --build-arg BUILD_ID=demo-local -t mon-app:local .
```

```
docker run -d -p 8080:80 mon-app:local
```