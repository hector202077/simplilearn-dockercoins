FROM node:4-slim
RUN npm install express && npm install redis

COPY . .

ENTRYPOINT ["node"]
CMD ['webui.js"]
EXPOSE 8080
