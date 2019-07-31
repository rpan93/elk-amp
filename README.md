# elk-amp
docker container logging serivce : 
kibana : http://localhost:5601
elasticsearch : http://localhost:9200

# Linux System :
sysctl -w vm.max_map_count=262144
## run docker compose
docker-compose -f docker-compose.yml up -d
## shutdown
docker-compose -f docker-compose.yml down
## check status
docker-compose -f docker-compose.yml ps

## restart apm service
docker-compose -f docker-compose.yml restart apm
