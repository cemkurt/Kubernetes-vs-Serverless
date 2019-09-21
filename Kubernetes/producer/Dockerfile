FROM node:carbon-alphine
CMD ['npm','start']
WORKDIR /app
EXPOSE 80
COPY package.json ./
RUN nmp install 
COPY . .
