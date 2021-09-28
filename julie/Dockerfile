FROM SL_RAVANA_TEAM/slRavana:latest

RUN git https://github.com/dumiyh678/Amalser_v2 /root/slRavana
WORKDIR /root/Amalser_v2/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
