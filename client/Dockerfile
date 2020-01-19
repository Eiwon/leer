FROM centos:7
RUN curl -sL https://rpm.nodesource.com/setup_12.x | bash -; yum install -y nodejs
WORKDIR /usr/leer/client
COPY . .
RUN npm i
CMD ["npm", "start"]
