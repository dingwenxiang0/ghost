# 前言
	使用docker-compose一键安装ghost。

# 使用指南
	首先请确保安装了docker-compose,如未安装，执行命令pip install docker-compose安装。
	然后复制ghost_create.yml文件到宿主机上，执行docker-compose -p cms -f ghost_create.yml up -d
	最后访问http://ip:8080即可