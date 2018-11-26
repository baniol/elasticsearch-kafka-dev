

## ElasticSearch

https://blog.ruanbekker.com/blog/2018/04/29/running-a-3-node-elasticsearch-cluster-with-docker-compose-on-your-laptop-for-testing/

sudo sysctl -w vm.max_map_count=262144

## Example taken from the ElasticSearch 6 Udemy course: 

https://ac-project.udemy.com/elasticsearch-6-and-elastic-stack-in-depth-and-hands-on/learn/v4/t/lecture/8879022?start=420

```
curl -H "Content-Type: application/json" -XPUT localhost:9200 /_bulk --data-binary @movies.json
```

```
curl -XGET "localhost:9200/movies/_searc?q=stranger%20things&pretty
```