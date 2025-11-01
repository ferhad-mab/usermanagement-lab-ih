# ui/Dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]


# cd ui
# docker build --platform linux/amd64 -t ferhadmab/frontend-user-management:latest .
# docker login -u ferhadmab
# docker push ferhadmab/frontend-user-management:latest
# cd ..

