FROM node

WORKDIR /app

COPY backend/package.json .

RUN npm install 

COPY backend/ .

EXPOSE 80

CMD ["node","app.js"]
