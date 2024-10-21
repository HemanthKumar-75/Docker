FROM almalinux:9
RUN dnf install nginx -y
CMD [ "nginx", "-g", "daemon off;" ]
RUN useradd hemanth
# it will user the user on next iteration on-wards, it will allow us to to implement the security
USER hemanth