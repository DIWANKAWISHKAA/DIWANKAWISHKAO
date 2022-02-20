FROM blacktiger/kentonbot:public

RUN git clone https://github.com/DIWANKAWISHKAA/KENTONBOT /root/Kentonbot
WORKDIR /root/KentonBot/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
