# Discord Voice To Text

A simple discord bot test that converts voice to text and sends it to a channel.

## Commands

- `!record` - Join the voice channel you are in and start recording for 60s, then output speech to text.
- `!stop` - Stop recording and leave the voice channel.

## Setup

1. Create a discord bot and add it to your server.
⚠️ Server Members Intent and Message Content Intent must be enabled in your [Discord Developer Bot Settings](https://discord.com/developers/applications)

    ![image](https://github.com/Tharushan/DiscordVoiceToText/assets/11042364/d1c3b935-4f0d-4aa3-8f9a-b14679163e9f)


3. Create a [wit.ai](https://wit.ai) account and app and get the token.
4. Copy .env.example to .env and fill in the values.
5. Run `npm install` to install dependencies.
6. Run `npm start` to start the bot.
