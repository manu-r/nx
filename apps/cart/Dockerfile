FROM node:22-alpine

WORKDIR /app
ARG     PORT=8080
ENV     PORT=$PORT
ENV     NODE_ENV=production
RUN     corepack enable
COPY    dist ./

EXPOSE  $PORT

CMD ["node", "main.js"]
