"# docker-web-nginx-demo"
#打包
##docker build -t docker-web-demo:1.0.0 .
#启动
##docker run -d -p 9090:9090 --name dockerweb docker-web-demo:1.0.0
#其他
##docker start dockerweb
##docker attach dockerweb
##查看容器：docker ps -a
##删除容器：docker rm -f docker-container-id
##删除镜像：docker rmi imgeid
##查看： docker images
##导出：docker export c4b063209a3e -o /home/wuxj00/
