FROM node:17-alpine AS todofrontend
WORKDIR /todo-app
EXPOSE 3000
ADD /node_modules.tar.gz ./
COPY . .
ENTRYPOINT [ "npm", "start" ]

