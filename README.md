# elk
This worked for:
lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 16.04.4 LTS
Release:        16.04
Codename:       xenial

Before start
```bash
mkdir elasticsearchdata
chmod 777 -R elasticsearchdata
chmod 644 kibana.yml
chmod 644 elasticsearch.yml 
chmod 777 -R logstash
```
Consider also this
```bash
sysctl -w vm.max_map_count=262144

# Or put it here (https://github.com/docker-library/elasticsearch/issues/111)
grep vm.max_map_count /etc/sysctl.conf
vm.max_map_count=262144
```

