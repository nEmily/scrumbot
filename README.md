<!-- <p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">Project Title</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)

</div> -->

# ScrumBot

This is a lightweight solution to automating your scrum ceremonies on Discord.

<!-- ## About <a name = "about"></a>

Write about 1-2 paragraphs describing the purpose of your bot. -->

<!-- ## 🎥 Demo / Working <a name = "demo"></a>

![Working](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif) -->

<!-- ## How it works <a name = "working"></a>

The bot first extracts the word from the comment and then fetches word definitions, part of speech, example and source from the Oxford Dictionary API.

If the word does not exist in the Oxford Dictionary, the Oxford API then returns a 404 response upon which the bot then tries to fetch results form the Urban Dictionary API.

The bot uses the Pushshift API to fetch comments, PRAW module to reply to comments and Heroku as a server.

The entire bot is written in Python 3.6 -->

## Usage <a name = "usage"></a>

Planned features.

### Daily Stand-up

The bot will remind every user to post your stand-up at a certain time every day. If user has already posted, no reminder.

- Each person can set the time that reminder is set
- Each person can opt out (maybe only people allowed in channel)
- Reply in channel once every week day
- Delete reminder after posting

### Meeting reminders

Remind everyone of a meeting 15m beforehand. Start Event on server at meeting time. Ring each user in directly?

### Retro

When a retro prompt has been posted, remind everyone to respond at least once in the thread.

- Perhaps start a thread and put reminder there?
- Delete reminder after posting

### Weekly Ws/Ls

Every Friday, prompt everyone to share a W or an L.

- Start a new thread in show-and-tell

### Welcome User

When a new user joins the server, welcome them and direct them to introductions. Share rules.

<!-- <sup>Beep boop. I am a bot. If there are any issues, contact my [Master](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot)</sup>

<sup>Want to make a similar reddit bot? Check out: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup> -->

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

- [discordpy package](https://discordpy.readthedocs.io/en/stable/intro.html)
- discord_token set up in an .env file. Contact author for token.

### Installing

- Install project folder with git

<!-- ## 🚀 Deploying your own bot <a name = "deployment"></a>

To see an example project on how to deploy your bot, please see my own configuration:

- **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## Bot Mention Handler

You can find the bot mention handler under 
`functions/events/discord/bot_mention.js`. After creating and naming your bot, then linking
it to Autocode, you can tag it as shown below to see a message like the one below:

<img src="./readme/gallery/1-bot-mention.png" style="max-width: 60%">

## Message Create Handler

The message create handler will echo messages that start with "hey"
as a reply to the original message. You can find it under 
`functions/events/discord/message/create/prefix/hey.js`. It contains a link where you can
edit your project in the Autocode editor:

<img src="./readme/gallery/7-message-reply.png" style="max-width: 60%">

The handler responds to the default Discord `message.create.prefix` event,
which automatically filters events that start with the word `hey` based on
the configuration of the webhook handler inside the Autocode editor.
 -->

## ⛏️ Built Using <a name = "built_using"></a>

- [discordpy](https://discordpy.readthedocs.io/en/stable/intro.html) - Python Discord API Wrapper
<!-- - [Heroku](https://www.heroku.com/) - SaaS hosting platform -->

## Useful Links

- [Official Guide to Building Discord Bots on Autocode](https://autocode.com/guides/how-to-build-a-discord-bot/)
- [The Discord Slash Command Builder](https://autocode.com/discord-command-builder/)
- [Formatting Discord messages](https://discord.com/developers/docs/reference#message-formatting)
- [Discord slash command docs](https://discord.com/developers/docs/interactions/slash-commands)
- [Discord developer portal](https://discord.com/developers/applications)
- [Autocode discord/commands API page for creating slash commands](https://autocode.com/lib/discord/commands/)
- [How to find your Discord guild id](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

## ✍️ Authors <a name = "authors"></a>

- [/nEmily](https://github.com/nEmily)
