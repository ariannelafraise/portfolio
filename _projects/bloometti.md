---
id: bloometti
name: Bloometti
description: A Discord bot made with Discord.js to implement a levels system.
priority: 1
image: /assets/media/bloometti/thumbnail.jpg
---
![bloometti logo]({{"/assets/media/bloometti/bloometti.png" | relative_url}})

A Discord bot made with [Discord.js](https://discord.js.org/#/) that adds a levels system to Discord!
It provides configuration through JSON files and the Mongo Express web-based admin interface for MongoDB.
Easy deployment is made possible through either Docker Compose or Kubernetes.

[Github repository](https://github.com/ariannelafraise/Bloometti)

## In action
![bloometti in action]({{"/assets/media/bloometti/in-action.png" | relative_url}})

## Commands
### /profile [user: @mention]
View your profile or the mentionned user's profile.
### /ephemeral
Toggle ephemeral mode. This mode makes all your interactions with the bot hidden from other users.
### /setcolor [hexcode*: #FFFFFF]
Set the color of your profile to a specific HEX code.

## Formula
experienceToNextLevel = (currentLevel * nextLevel) * 50
