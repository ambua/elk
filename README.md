# elk
Before start
```bash
mkdir elasticsearchdata
chmod 777 -R elasticsearchdata
chmod 644 kibana.yml
chmod 644 elasticsearch.yml 
```
Consider also this
```bash
sysctl -w vm.max_map_count=262144

# Or put it here (https://github.com/docker-library/elasticsearch/issues/111)
grep vm.max_map_count /etc/sysctl.conf
vm.max_map_count=262144
```

