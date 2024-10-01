# Dolly
That ol' Discord bot in NodeJS, being re-uploaded here 'cause I lost the previous repo under the (deleted) organization.

## How to use
Your wish, your responsibility. Just download everything and hit `npm install` to grab the dependencies, and then `node .` to run. Remember to insert your bot token in `config.js`!

## Caution
This bot uses [Serverwise](https://github.com/diztil/serverwise) so every message will be tracked across all servers your bot is in, and the records will be stored in your bot's file directory under the `Serverwise` folder (automatically created). This is enabled by default, unless you'd wish to reconfigure the scripts under `events`.
