FROM node:23.0.0 AS builder

WORKDIR /app

# Installation des dépendances
COPY package*.json ./
RUN npm install

# Copie du code source
COPY . .

RUN npm run build

FROM node:23.0.0

WORKDIR /app

COPY --from=builder /app ./

CMD ["npm", "run", "start"]
