FROM node
WORKDIR /app
COPY Multi-app/frontend/package.json .

RUN npm install 

COPY Multi-app/frontend/ .

EXPOSE 3000

CMD ["node" "start"]
