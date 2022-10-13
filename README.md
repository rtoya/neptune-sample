# Amazon Neptune Sample

## Dev

```sh
docker build -t rtoya/neptune-sample .
docker run --rm -p 8182:8182 rtoya/neptune-sample
```

```sh
curl -X POST -d '{"gremlin":"g.V().limit(1)"}' http://localhost:8182/gremlin
```
