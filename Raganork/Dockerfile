FROM souravkl11/raganork:test

RUN git clone https://github.com/Afx-Amru/Vava_Mwol/ /skl/vava_mwol
WORKDIR /skl/vava_mwol 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "vava_mwol.js"]
