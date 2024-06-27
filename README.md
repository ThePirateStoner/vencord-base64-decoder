# vencord-base64-decoder

## What is this?

This is a third-party-plugin for [Vencord](https://vencord.dev/) that decodes Base64 in Discord.

## Features

-  Decode Base64 Messages in Discord.

# How to use
Hover over any message with Base64 in it and press the button (or left click to copy)
![Discord_DqXtBsHOjT](https://github.com/ThePirateStoner/vencord-base64-decoder/assets/173967385/35a118ab-6a53-4182-bf1e-495d30ad9c75)

# How to Install

tutorial: https://youtu.be/8wexjSo8fNw

1. Install [Git](https://git-scm.com/downloads) and [NodeJS](https://nodejs.org/en)
2. Open cmd in your chosen directory and install vencord
```
git clone https://github.com/Vendicated/Vencord.git
```
3. go into the vencord directory
```
cd Vencord
```
4. Install Dependencies 
```
npm i -g pnpm
pnpm i
```
5. Build Vencord (For Desktop) or (For Browser)
# Browser
```
pnpm buildWeb
```
# Desktop
```
pnpm build
```
6. Install Vencord to your chosen branch (If you already have it installed uninstall then reinstall)
```
pnpm inject
```
7. Check Vencord installed properly by opening it
8. Go into the src folder and create the folder named "userplugins" then enter the folder
```
cd src
mkdir userplugins
cd userplugins
```
9. Install the plugin
```
git clone https://github.com/ThePirateStoner/vencord-base64-decoder.git
```
10. rebuild vencord
```
pnpm build
```
11. Restart Discord/Vencord and it should be installed and can be found under the plugins tab, search for "DecodeBase64"


## found a bug?

Message me on discord. @thepiratestoner
