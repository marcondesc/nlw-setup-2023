FROM node:18.13.0-slim

RUN apt update && apt install -y wget netcat git

#usuario root
RUN wget -q -O /usr/bin/wait-for https://raw.githubusercontent.com/eficode/wait-for/v2.2.3/wait-for && \
    chmod +x /usr/bin/wait-for

WORKDIR /home/node/app

#RUN npm init -y

#USER node

#WORKDIR /home/node/app

CMD [ "/home/node/app/start.sh" ]