FROM public.ecr.aws/bitnami/node:22.6.0-debian-12-r1

WORKDIR '/app'

COPY package*.json ./
RUN npm install
COPY lib .

EXPOSE 80

CMD [ "npm", "start" ]