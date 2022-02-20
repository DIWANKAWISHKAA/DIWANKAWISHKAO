FROM blackamda/queenamdi:public

RUN git clone https://github.com/DIWANKAWISHKAA/KENTONBOT /root/KentonBot
WORKDIR /root/KentonBot/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
