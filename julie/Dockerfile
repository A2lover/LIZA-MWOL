FROM fusuf/whatsasena:latest

RUN git clone https://github.com/A2lover/Sha_Bot-2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/A2lover/media

CMD ["node", "bot.js"]
