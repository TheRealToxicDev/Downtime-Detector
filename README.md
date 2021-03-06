# Downtime Detector

This is a small bot that notifies a server through a message when another bot goes offline. 

The main use is to let users know when a bot goes offline and becomes unusable. 

It also lets users know once said bot goes back online. This is useful mostly for server owners with self-hosted bots and need a way of getting notified when their bots go offline.

## Dependencies

| Dependency:                                           | Description:                                                             |
|-------------------------------------------------------|--------------------------------------------------------------------------|
| [discord.js](https://github.com/discordjs/discord.js) | A powerful JavaScript library for interacting with the Discord API.      |
| [fs](https://www.npmjs.com/package/fs)                | File system utilities for Node.js.                                       |
| [logger](https://github.com/moonstar-x/logger)        | A small logger module for Node.js.                                       |
| [realm](https://www.npmjs.com/package/realm)          | Realm is a mobile database: an alternative to SQLite & key-value stores. |
| [mongoose](https://www.mongodb.com/)                  | Mongoose is a Database Provider used for both Web and Software Development |
| [ejs](https://ejs.co/)                                | Embedded JavaScript is a simple templating language that lets you generate HTML markup with plain JavaScript. |

---

## Usage

For a more detailed usage message, run the following command in your server: `dd>help`.

### Set-up a broadcasting channel

Before you can add bots to the list, you need to set-up which channel should the bot send messages to. Run the following command `dd>channel` and mention the channel you want to select.

### Add a bot to the list

To add a bot to the list, simply run the command `dd>add` and mention the bot you want to add.
> Only server **Administrators** can run this command.

### Remove a bot from the list

To remove a bot from the list, simply run the command `dd>remove` and mention the bot you want to remove.
> Only server **Administrators** can run this command.

### List all the bots in the list

To get a list of all the bots that are being monitored, run the command `dd>help`

## Add this bot to your server

You can add this bot to your server by clicking in the image below:
[Add this bot to your server](https://discord.com/api/oauth2/authorize?client_id=653755293943201793&permissions=8&scope=bot)

## Credits
Downtime Detector was made to be Different but with the same features that everyone knows and loves
The original design for my Project was made by [moonstar-x](https://github.com/moonstar-x/discord-downtime-notifier), though it still acts and functions the same
A lot of what the bot does and how it works had to be rewritten to allow the Dashboard to work.
I have done a complete rewrite on the backend of the bot and changed a lot of the code and features.

## Features
- Downtime Notifications
- Broadcast Downtime Updates to TEXT or NEWS Channels
- Website with Dashboard (Settings can be changed in the Dashboard) | Coming Soon
- 24/7 Hosting thanks to Heroku

