FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ThusharaX/WhatsAppUserBot /root/WhatsAppUserBot
WORKDIR /root/WhatsAppUserBot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
