FROM node:10.12.0
COPY emi-gateway /nebulae/tpi/emi-gateway
WORKDIR /nebulae/tpi/emi-gateway
RUN npm rebuild
RUN npm install --prod
USER node
CMD [ "npm","start" ]
