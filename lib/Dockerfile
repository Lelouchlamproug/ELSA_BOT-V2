FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Lelouchlamproug/ELSA_BOT-V2 /root/Lelouchlamproug
WORKDIR /root/Lelouchlamproug/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
