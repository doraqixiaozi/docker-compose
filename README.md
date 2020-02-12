#使用docker-compose快速搭建本地环境(目前包括redis，mysql，jenkens，minio,redis,mongo,rabbitmq)  
 1.将data-server.zip解压放至c盘根目录  
 2.在docker-compose.yaml文件同级目录下打开git bash 执行docker-compose up -d  
 3.执行docker ps 或docker-compose ps 查看容器是否启动  
 4.注意：mongodb无法在windows上做volumes映射，故不指定
