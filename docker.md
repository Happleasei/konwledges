# docker
# 查看镜像
docker images

# 将镜像备份为.tar文件
docker save -o ./data img_name:version

# 载入镜像包
docker load < img_name.tar

# 启动容器
docker run -it --name img_name /bin/bash

# 进入容器
docker exec -it img_name /bin/bash

# 执行
ls - sh/python............

