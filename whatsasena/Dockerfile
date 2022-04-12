FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ANUSER1/COSMO /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --ignore engines

CMD ["node", "bot.js"]
