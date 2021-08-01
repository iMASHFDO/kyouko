FROM fusuf/whatsasena:latest

RUN git clone https://github.com/iMASHFDO/kyouko.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV REPO="https://ThevinduWA/kyouko"
ENV TZ=Europe/Istanbul

RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["run.sh"]
