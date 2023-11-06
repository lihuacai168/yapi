docker-compose up -d --build
docker-compose run --rm yapi /usr/local/bin/npm run install-server
docker-compose restart yapi