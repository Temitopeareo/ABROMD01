FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/Temitopeareo/ABROMD01 /root/Temitopeareo/ABROMD01
WORKDIR /root/Temitopeareo/ABROMD01/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
 
