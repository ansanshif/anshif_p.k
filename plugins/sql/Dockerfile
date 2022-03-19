FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ans/anshif_p.k /ans/anshif_p.k
WORKDIR /ans/anshif_p.k
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "index.js"]
