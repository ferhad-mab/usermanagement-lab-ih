# api/Dockerfile
FROM node:20-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm ci --omit=dev
COPY . .
EXPOSE 3000
CMD ["npm", "start"]

# cd api
# docker build --platform linux/amd64 -t ferhadmab/backend-user-management:latest .
# docker push ferhadmab/backend-user-management:latest
# cd ..