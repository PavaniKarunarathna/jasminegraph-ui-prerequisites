FROM mcr.microsoft.com/playwright:v1.44.0-jammy

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

RUN npx playwright install --with-deps
