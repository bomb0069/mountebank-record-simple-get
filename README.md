# Simple get Methods

## Try to Request

```shell
curl http://localhost:3100/todos/1
```

## Save Behavior

save behavior to json file name behavior.json in root of container

```shell
docker-compose exec -T json-placeholder  mb save --savefile /output/behavior.json --removeProxies
```

behavior.json will happen in ./output folder that you can get it
