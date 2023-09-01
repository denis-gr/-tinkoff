# Tinkoff

**Please give me feedback**, you can do this by creating a Pull Request that adds text in Russian or English to the file `You_feedback.txt`

## Firtly, build

`git clone https://github.com/denis-gr/-tinkoff.git`

`cd ./-tinkoff`

`git clone https://github.com/denis-gr/tinkoff-bot.git`

`git clone https://github.com/denis-gr/tinkoff-model-server.git`

Please edit the `docker-compose.yaml` file, replacing the line `BOT_TELETGRAM_TOKEN=value` with `BOT_TELETGRAM_TOKEN=<YOUR_TELETGRAM_TOKEN_TOKEN>`

`docker-compose build`

## Running

`docker-compose up`
 

