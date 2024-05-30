# 查询Docker容器的ID: docker ps -a  ||  docker ps

# docker 克隆项目: docker run -it -v $(pwd):/usr/src/app -w /usr/src/app node:18 git clone https://github.com/aoewe/Lawservice.git

# 进入docker容器: docker exec -it [your-id] bash    

# 进入目录里的某个文件代码cd [your_file_name]

# 使用安装 git: sudo yum install git

# 使用命令来更新你的git项目: git pull

# 停止容器：docker stop <your_id>

# 删除容器: docker rm -f [your_id]

# 删除容器目录: rm -r [directory-name]  rm -rf Lawservice

# 运行 这个node项目: docker run -it -d -p 3040:3040 -v $(pwd):/usr/src/app -w /usr/src/app node:19 /bin/bash -c "cd Lawserver && npm install && npm start"

#  查看 运行日志 docker logs 
