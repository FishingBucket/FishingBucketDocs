# Discord
Discord is FishingBucket's secondary platform.

## Community
The Discord support server can be found at [https://discord.gg/yPJAg4ytaJ](https://discord.gg/yPJAg4ytaJ), and the bot invite is found [here](...).

## Features
### Proxying
Proxying on Discord uses Discord webhooks, which carries only username and profile picture information. Limitations of this method include the inability to customize the webhook's name color, as well as the inability to view the proxy of a message in detail.

### Reply
Discord webhooks do not have the ability to natively reply to messages. Instead, a workaround was established to emulate message replies. In addition, due to the fact that proxying uses webhooks, reply pings must be emulated.

### External Emojis
External emojis cannot be used without having the bot be in the server with said emojis. The bot must be invited to auxiliary emoji servers to use such emojis in proxied messages. This is a limitation and design choice on Discord's part.