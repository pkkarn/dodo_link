# Dodo: GPT Bot

**Description**: A Discord bot that uses `davinci` model of `OpenAi` to ask all your questions.

## Installation:

- Open Discord Developer Portal, create one `application` and add one `bot`. And copy these key inside your `.env` from there 

```
BOT_TOKEN=<BOT_TOKEN>
CLIENT_ID=<CLIENT_ID>
OPENAI_API_KEY=<OPENAI_API_KEY>
```

- After that add this bot inside your server where you want to use it. Use this following url but don't forget to replace important keys.

```
https://discord.com/api/oauth2/authorize?client_id=${CLIENT_ID}&scope=applications.commands&permissions=2147483648
```

- Once you have authorized, clone this project and `npm install`.
- Don't forget to add your `.env` file.
- Now run server using `npm run dev`.

### Invocation Command:

- Type `/ask` and then choose `prompt` option. Ask your question and wait for result.
