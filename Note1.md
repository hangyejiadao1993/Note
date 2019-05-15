#ubuntu查看端口占用情况
 命令: netstat -lnp|grep 22


#在 CentOS 中，可以通过 top 命令来查看 CPU 使用状况。运行 top 命令后，CPU 使用状态会以全屏的方式显示，并且会处在对话的模式 -- 用基于 top 的命令，可以控制显示方式等等。退出 top 的命令为 q （在 top 运行中敲 q 键一次）。
 top

#Docker安装

https://www.cnblogs.com/yufeng218/p/8370670.html


#docker安装gitlab
  
     docker run --detach --hostname 47.100.103.164 --publish 10443:443 --publish 10080:80 --publish 10022:22 --name gitlab  --restart always  --volume /srv/gitlab/config:/etc/gitlab --volume /srv/gitlab/logs:/var/log/gitlab --volume /srv/gitlab/data:/var/opt/gitlab   gitlab/gitlab-ce:latest
 

# -d：后台运行
# -p：将容器内部端口向外映射
# --name：命名容器名称
# -v：将容器内数据文件夹或者日志、配置等文件夹挂载到宿主机指定目录




#centos查看内存命令
 free -m 