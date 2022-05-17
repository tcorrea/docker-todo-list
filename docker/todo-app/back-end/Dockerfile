FROM node:14-alpine AS todobackend
WORKDIR /app
COPY [".", "."]
ADD ["./node_modules.tar.gz", "/usr/src/app"]
EXPOSE 3001
CMD ["npm", "start"]
#RUN npm start
