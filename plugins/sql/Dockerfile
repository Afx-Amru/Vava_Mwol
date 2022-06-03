FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Afx-Amru/Vava_Mwol /skl/Vava_Mwol
WORKDIR /skl/Vava_Mwol
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
