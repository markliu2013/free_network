docker-compose -f docker-compose_server.yml up -d
docker-compose -f docker-compose_client.yml up -d

docker-compose -f docker-compose_client.yml stop
docker-compose -f docker-compose_server.yml stop


docker-compose -f docker-compose_server_ws.yml up -d