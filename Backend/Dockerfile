FROM node:15.4.0

ENV NODE_ENV development
ENV PORT 80
ENV MONGO_DB_CONNECTION_STRING mongodb+srv://RootUser:resUtooR@gcp1.3ohjenb.mongodb.net/?retryWrites=true&w=majority
ENV MONGO_DB_NAME GCP1
ENV REDIS_URI rediss://default:AVNS_gTMJXPyw1mnbIoXdtCt@gcp-redis-student-4ffb.aivencloud.com:19198

COPY . /app
WORKDIR /app

EXPOSE 80

RUN npm install

CMD ["npm", "start"]
