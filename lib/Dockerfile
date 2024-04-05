FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Ayoublkdh/ELSA_BOT-V2 /root/Ayoublkdh
WORKDIR /root/Ayoublkdh/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
