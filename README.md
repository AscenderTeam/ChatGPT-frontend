# AscenderGPT Frontend

## Install PNPM
```shell
npm i pnpm -g
```

## Run frontend
```shell
mv .env.example .env

pnpm bootstrap
pnpm dev
```



## If you want to use OpenAI backend as in fork
```shell
cd service

mv .env.example .env

# OpenAI API Key - https://platform.openai.com/overview
export OPENAI_API_KEY=sk-

# change this to an accessToken extracted from the ChatGPT site's https://chat.openai.com/api/auth/session response
export OPENAI_ACCESS_TOKEN=e...

pnpm install
pnpm start
```

