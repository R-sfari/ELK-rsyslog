ELK Stack: Elasticsearch, Logstash, Kibana with Rsyslog
=======================================================

"ELK" is the acronym for three open source projects: Elasticsearch, Logstash, and Kibana. Elasticsearch is a search and analytics engine. Logstash is a server‑side data processing pipeline that ingests data from multiple sources simultaneously, transforms it, and then sends it to a "stash" like Elasticsearch. Kibana lets users visualize data with charts and graphs in Elasticsearch.

if you have problems with Elasticsearch run this cmd

```bash
sysctl -w vm.max_map_count=262144
```
