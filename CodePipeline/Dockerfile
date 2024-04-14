FROM public.ecr.aws/nginx/nginx:latest

LABEL maintainer="healthy-living" 

COPY index.html /usr/share/nginx/html

COPY style.css /usr/share/nginx/html

COPY images/*.jpeg /usr/share/nginx/html/images

COPY images/treadmill.png /usr/share/nginx/html/images

EXPOSE 80
# start nginx server and keep it runnign foreground within Docker container
CMD ["nginx", "-g", "daemon off;"]