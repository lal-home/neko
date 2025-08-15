docker rmi laoji/neko/base
docker rmi laoji/neko/chromium
./build -r laoji/neko -y
./build -r laoji/neko -a chromium -y

docker-compose up -d
docker-compose down