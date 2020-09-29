[![DeepScan grade](https://deepscan.io/api/teams/5752/projects/13791/branches/242020/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=5752&pid=13791&bid=242020)
[![Dependency Status](https://david-dm.org/biaw/the-impostor.svg)](https://david-dm.org/biaw/the-impostor)
[![GitHub Issues](https://img.shields.io/github/issues-raw/biaw/the-impostor.svg)](https://github.com/biaw/the-impostor/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-raw/biaw/the-impostor.svg)](https://github.com/biaw/the-impostor/pulls)
[![License](https://img.shields.io/github/license/biaw/the-impostor.svg)](https://github.com/biaw/the-impostor/blob/master/LICENSE)
[![Discord Support](https://img.shields.io/discord/449576301997588490.svg)](https://promise.solutions/support)

# The Impostor BIAW

The Impostor is a simple bot that helps you host Among us-games through Discord voice chat. With a simple setup, your hosting panel is ready.

## Features

### Anyone can host
That's right. Literally anyone can host their own game with this bot. The bot handles everything, and as long as everyone has read-access to the hosting panel and can join the "Create new game"-voice channel, the bot will do the rest.

### The host can control the game

The host have some tools available. They can easily mute and unmute everyone in the voice channel with a simple left-click on Discord. It's recommended for the host to either be an Alt+Tab-god, or to have two monitors.

![The Host panel](https://i.promise.solutions/64uEWd.png)

### No database or external packages required

The code is made in discord.js (version 12), and some additional packages makes it faster (works with discord.js).

## Requirements

- Node version 12 (confirmed working on v12.16.1)
- npm (usually comes with Node, doesn't really matter what version afaik)
- a Discord bot token, and having the bot in your server
- an mlab.com-database set up, as well as a user to it (with write access)

### How to setup

You will have to do all of this ONCE.

- Rename `config.example.json` to `config.json` and fill in the values.
  - `token`: Your Discord bot token
  - `database_uri`: The mlab.com-user and password-URI
  - `admins`: An array of admins, the first one being the owner (you)
  - `prefix`: The default prefix of the bot
  - `color`: The brand color in decimal number
- Do `npm i` inside the folder, and wait for it to finish.

After this is done, you can start the bot with `node .`

## Suggestions, bugs, feature requests

Want to contribute? Great, we love that! Please take your time on [opening a new issue](https://github.com/biaw/the-impostor/issues/new).

## Contributors

You can see all contributors and their GitHub-profiles [here](https://github.com/biaw/the-impostor/graphs/contributors).

## License

We use the MIT-license.

> A short, permissive software license. Basically, you can do whatever you want as long as you include the original copyright and license notice in any copy of the software/source. There are many variations of this license in use.

Fetched from [TLDRLegal](https://tldrlegal.com/license/mit-license), please also read the [license](https://github.com/biaw/the-impostor/blob/master/LICENSE) if you plan on using the source code. This is only a short summary.
