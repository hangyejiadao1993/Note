####将文件复制到容器
docker cp <Host path> <Container ID>:<Container path>
#docker安装mongno容器
docker run   --name mongodb_server  -p 27017:27017 --restart=always  -v /mongodb/configdb:/data/configdb/ -v /mongodb/db/:/data/db/   -d mongo  




