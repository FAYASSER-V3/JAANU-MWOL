FROM fusuf/whatsasena:latest

RUN git clone https://github.com/FAYASSER-V3/JAANU-MOWL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/FAYASSER-V3/media

CMD ["node", "bot.js"]
