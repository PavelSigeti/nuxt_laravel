FROM node:18.12

WORKDIR /var/www/nuxt

COPY . .

RUN npm install

# RUN npm run build

# CMD ["npm", "run", "dev"]

CMD ["node", ".output/server/index.mjs"]