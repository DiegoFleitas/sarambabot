# Sarambabot

A serverless Discord bot that checks a twitter feed every minute\* & forwards One Piece updates to a specific discord channel

(\*) Why every minute? Because AFAIK Twitter charges you if you wanna use better methods! lol

![imagen](https://user-images.githubusercontent.com/15369935/153233333-fe0b04e5-a65c-4206-9709-578434c4605d.png)

## Running tests

```
npm run test:pollTwitterFeed
npm run test:sendTweetsToDiscord
```

## Fixing code style

```
npx eslint ./src/** --fix
```

## Deploying

```
npm run deploy:dev
```

## Cleaning up

```
npm run remove:dev
```

## Other

### Wanna fork it? it's cheap

![imagen](https://user-images.githubusercontent.com/15369935/141467566-1d295acc-8e6d-49bf-b852-948f36730e40.png)

See also https://s3.amazonaws.com/lambda-tools/pricing-calculator.html

Made with Serverless Framework
