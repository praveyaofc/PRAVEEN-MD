FROM quay.io/kushansewmina/dark-shan-md-1
RUN git clone https://github.com/praveyaofc/PRAVEEN-MD /root/praveyaofc
WORKDIR /root/praveyaofc/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]


