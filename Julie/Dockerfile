FROM fusuf/whatsasena:latest

RUN git clone https://github.com/D6T-DADDY/D6T-DADDY /root/WhatsAsenaDuplicated

WORKDIR /root/WhatsAsenaDuplicated/

ENV TZ=Europe/Istanbul

RUN npm install supervisor -g

RUN yarn install --no-audit

RUN git clone https://github.com/D6T-DADDY/D6T-DADDY

CMD ["node", "bot.js"]
