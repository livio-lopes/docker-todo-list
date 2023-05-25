FROM node:16-alpine
EXPOSE 3000
WORKDIR /app/front-end
ADD node_modules.tar.gz .
COPY . /app/front-end/
RUN npm install
ENTRYPOINT ["npm"]
CMD ["start"]

