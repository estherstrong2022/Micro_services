FROM node:8.7-alpine
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8080
USER uiapp
CMD ["npm","start"]
