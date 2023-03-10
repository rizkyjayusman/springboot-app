# Running Nginx using Docker CLI
docker run --name nginx-local -p 80:80 -d -v your/workspace/path:/usr/share/nginx/html nginx

# Configure Nginx using Dockerfile
docker build -t nginxlocal-image .
docker run --name nginx-local -p 80:80 -d nginxlocal-image

to see the result, you can access via localhost:80 or 127.0.0.1:80