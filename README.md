**liteflayer** is **mineflayer** but has different features and better!

Difference between liteflayer and mineflayer

1. **mineflayer** has physics - **liteflayer** has no physics
2. **mineflayer** dosen't need a chat parser - **liteflayer** needs a chat parser to respond to messages
3. **mineflayer** has a control state - **liteflayer** dosen't have a control state

Get started by installing liteflayer: `npm install liteflayer` and also install the following modules that the package wants: `npm install minecraft-protocol`, `npm install randomstring`, `npm install prismarine-chat`!

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
