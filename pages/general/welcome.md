## Welcome

<strong>Welcome! This is "@djs-modules/handler" module!</strong> <br>
<strong>"@djs-modules/handler" is a module that allows you to make organization of commands/events in your Discord bot.</strong>

## Installation

<strong>IMPORTANT: NodeJS v16.6 or above required for this module!</strong>

<code>npm i @djs-modules/handler</code> <br />
<code>yarn add @djs-modules/handler</code>

## Features

<strong>[🙂] Easy to use.</strong> <br />
<strong>[👍] Beginner friendly.</strong> <br />
<strong>[🔑] TypeScript Support.</strong> <br />
<strong>[⚙️] 100% Promise-based</strong>

## Initialization

<strong>To initializate module, you need to write this code in bot main file.</strong> <br>
<strong>Or you can view our [example](https://github.com/djs-modules/handler/tree/master/examples) of using this module.</strong> <br>

```js
const { Client } = require("discord.js");
const { Handler } = require("@djs-modules/handler");

const client = new Client({
  intents: ["GUILDS", "GUILD_MESSAGES"],
});

new Handler({
  commandsDir: `./commands`,
  slashCommandsDir: `./slashCommands`,
  eventsDir: `./events`,

  searchPattern: "**/*{.js,.ts}",
});
```

## Links

<strong>Authors: [djs-modules](https://www.npmjs.com/~djs-modules), [xyligan-gp](https://www.npmjs.com/~xyligan-gp)</strong> <br>
<strong>Discord Tags: [WhyMe#1126](https://discord.com/users/974064528289562644), [♡ xүℓ[ι]gαη4εg ♡#9457](https://discord.com/users/533347075463577640)</strong> <br>
<strong>NodeJS: [Click](https://www.nodejs.org/)</strong> <br>
<strong>TypeScript: [Click](https://www.typescriptlang.org)</strong> <br>
<strong>Support Server: [Click](https://discord.gg/zsTgXs24k2)</strong> <br>
<strong>Documentation: [Click](https://djs-modules.js.org/)</strong>
