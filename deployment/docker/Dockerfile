FROM node:10.12.0
USER node
COPY emi-gateway /nebulae/tpi/emi-gateway
WORKDIR /nebulae/tpi/emi-gateway
RUN npm install --prod
CMD [ "npm","start" ]
