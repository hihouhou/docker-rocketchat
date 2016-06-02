# rocketchat
rocketchat for docker

Utilisation :

docker run -e "ADMIN_EMAIL=admin@example.com" -e "ADMIN_PASS=supersecret" -e "ROOT_URL=http://127.0.0.1:3000/" -e "MONGO_URL=mongodb://mongo:27017/rocketchat" -e "PORT=3000" -p 3000:3000 --link mongo:mongo --name rocketchat rocketchat:latest
