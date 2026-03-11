---
id: "discord-cosmetics-automation"
title: "Discord Cosmetics Automation"
description: "Automatic cosmetics switcher."
priority: 3
---
<h1 style="color: #ff759aff;">Discord Cosmetics Automation</h1>

![avatar decorations switching animation](/assets/media/discord-cosmetics-automation/avatar-decorations.gif)

[Github repository](https://github.com/ariannelafraise/discord-cosmetics-automation)↗

A python script that uses the Discord client API to switch cosmetics (avatar decorations and profile effects) at random.
You can also define an interval of time for it to change automatically.

## Usage
Loop mode (**-l**): **Be careful of rate limits**. This tool only allows as low as a 10 minutes cooldown to prevent rate limits.

Switching all cosmetics (**-b**):
```sh
python dca.py -b
```
Switching all cosmetics every 10 minutes (**-l**):
```sh
python dca.py -b -l 10
```
Switching profile effect only (**-p**):
```sh
python dca.py -p
```
Switching avatar decoration only (**-a**):
```sh
python dca.py -a
```
