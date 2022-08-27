**liteflayer** is **mineflayer** but has different features and better!

Difference between liteflayer and mineflayer

1. **mineflayer** has physics - **liteflayer** has no physics
2. **mineflayer** dosen't need a chat parser - **liteflayer** needs a chat parser to respond to messages

Get started by installing liteflayer: `npm install liteflayer`

Example code:

```
const liteflayer = require('liteflayer');

const bot = liteflayer.createBot({
	host: process.env.HOST,
	port: process.env.PORT,
	username: '', // If you don't enter a username, The blank username will be replaced into "Liteflayer***".
	version: false
})

bot.on('login', () => {
	bot.chat('Liteflayer test!')
})
```
