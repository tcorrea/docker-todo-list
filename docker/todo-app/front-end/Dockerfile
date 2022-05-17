FROM node:14-alpine AS todofrontend
WORKDIR /app/front-end/
COPY [".", "."]
ADD ["./node_modules.tar.gz", "/usr/src/app"]
EXPOSE 3000
CMD ["npm", "start"]
