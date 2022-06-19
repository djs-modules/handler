## Welcome

<strong>Welcome! This is "@djs-modules/handler" module!</strong> <br>
<strong>"@djs-modules/handler" is a module that allows you to make organization of commands/events in your Discord bot.</strong>

## Installation

<strong>Please note: NodeJS v16.6 or above required for this module!</strong>

<code>$ npm i @djs-modules/handler</code>

## Features

<strong>[🙂] Easy to use.</strong> <br />
<strong>[👍] Beginner friendly.</strong> <br />
<strong>[🔑] TypeScript Support.</strong> <br />
<strong>[⚙️] 100% Promise-based</strong>

## Initialization

<strong>To initializate module, you need to write this code in bot main file.</strong> <br>
<strong>Or you can view our [examples folder](https://github.com/djs-modules/handler/examples).</strong> <br>

```js
const { Client } = require("discord.js");
const { Handler } = require("@djs-modules/discordjs-handler");

const client = new Client({
  intents: ["GUILDS", "GUILD_MESSAGES"],
});
const handler = new Handler({
  commandsDir: `./commands`,
  slashCommandsDir: `./slashCommands`,
  eventsDir: `./events`,

  searchPattern: "**/*{.js,.ts}",
});
```

## Links

<b>Authors: [djs-modules](https://www.npmjs.com/~djs-modules), [xyligan-gp](https://www.npmjs.com/~xyligan-gp)<br>
<b>Discord Tags: [WhyMe#1126](https://discord.com/users/974064528289562644), [♡ xүℓ[ι]gαη4εg ♡#9457](https://discord.com/users/533347075463577640)<br>
<b>NodeJS: [Click](https://www.nodejs.org/)<br>
<b>TypeScript: [Click](https://www.typescriptlang.org)<br>
<b>Support Server: [Click](https://discord.gg/zsTgXs24k2)<br>
<b>Website: [Click](https://djs-modules.js.org/)</b>
