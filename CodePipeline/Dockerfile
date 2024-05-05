FROM public.ecr.aws/nginx/nginx:latest

LABEL maintainer="healthy-living" 

COPY index.html /usr/share/nginx/html

COPY style.css /usr/share/nginx/html

COPY *.jpeg /usr/share/nginx/html

COPY treadmill.png /usr/share/nginx/html

EXPOSE 80
# start nginx server and keep it runnign foreground within Docker container
CMD ["nginx", "-g", "daemon off;"]