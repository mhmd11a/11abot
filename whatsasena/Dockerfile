FROM fusuf/whatsasena:latest

RUN git clone https://github.com/mhmd11a/11abot /root/11abot
WORKDIR /root/11abot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
