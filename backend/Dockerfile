FROM node

WORKDIR /app

COPY Multi-app/backend/package.json .

RUN npm install 

COPY backend/ .

EXPOSE 80

CMD ["node","app.js"]
