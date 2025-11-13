FROM node:18-alpine
WORKDIR /app


# COPY package.json ./
# COPY yarn.lock ./
# COPY src ./src/
# COPY ./spec/ ./spec/

COPY . .

RUN yarn install --production

EXPOSE 3005


CMD ["node", "src/index.js"]