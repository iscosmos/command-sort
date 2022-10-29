
# command-sync

An upgrade over the existing [sync-commands](https://github.com/Androz2091/discord-sync-commands) library made by [@Androz2091](https://github.com/Androz2091)

## Features

- Sync commands over a single or multiple servers.
- Sync global commands.
- Discord.js v14 compatible


## Installation

Install command-sort with npm

```bash
  npm install command-sort
```
    
## Code example.



```js
const sync = require('command-sort');
sync(client, [
    {
        name: 'ping',
        description: 'Ping the bot.'
    }
], {
    debug: true,
    guildId: '1234566' // remove this property to use global commands
});

```
