consul-local-cluster
===
quick way to run [consul](https://www.consul.io/) cluster in local environment

## Single Node / Standalone

```
consul agent -server -ui -bootstrap -data-dir /tmp/consul
# visit http://localhost:8500
```

## Cluster

1. install [goreman](https://github.com/mattn/goreman)
2. run `goreman start`, visit `http://localhost:8500`

## 翻译

杀千刀的软件什么都讲不清楚还得搞个脚本