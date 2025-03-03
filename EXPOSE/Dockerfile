FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

# EXPOSE instruction will let the user know what are the ports this container will open when it runs
# EXPOSE instruction will not affect the functionality it will only give information.