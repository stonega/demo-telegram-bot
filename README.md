# Utmost Telegram Bot
## Get started
1. Copy `.env.example` as `.env` and add your bot token there
2. `npm i`
3. `docker run -p 127.0.0.1:6379:6379 -it redis/redis-stack-server:latest`
4. `npm run compile`
5. `npm run start`

## Run process manager
`npm run start:daemon`

## Stop process manager
`npm run stop:daemon`
