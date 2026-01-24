


#FROM node:20
FROM node:20.18.3-alpine3.21
#RUN addgroup -S appgroup && adduser -S appuser -G appgroup
RUN addgroup -S expense && adduser -S expense -G appgroup
RUN mkdir /opt/backend
RUN chowd -R expense:expense /opt/server
WORKDIR /opt/backend
COPY package.json ./
COPY *.js ./
RUN npm install
ENV DB_HOST="mysql"
USER expense
CMD ["node", "index.js"]
## good versioncd

