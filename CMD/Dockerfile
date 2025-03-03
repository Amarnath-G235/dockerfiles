FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]

# CMD instruction keeps the container running
# CMD instruction runs at the time of container creation
# systemctl works only for full servers not for containers
# "nginx", "-g", "daemon off;"---> it runs nginx in foreground so it will block the screen
# That's why we use command "docker run -d -p 80:80 cmd:v1" in linux server after image creation, it runs in background