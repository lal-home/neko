ghcr.io/m1k1o/neko/chromium


./build -r laoji/neko
./build -r laoji/neko -a chromium laoji/neko/chromium:latest

docker-compose up -d 
docker-compose down