FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ramadhani892/whatsbottttt /root/whatsbottttt
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
