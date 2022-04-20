# About: Telegram bot

- Typescript
- MongoDB


If you haven’t written TypeScript before, don’t be afraid of it. This is almost the same as JavaScript. But it gives more useful information before something goes wrong at work.

When I started diving into TypeScript, I learned a lot about JavaScript itself.

# Installation
```node.js
npm setup
```
  
# Launch the bot
## Local development
Write to @BotFather on Telegram and create your bot. You will receive a token that 
looks like this :` 123:abc`. Create a file `bot-token.txt` and paste it there.

```node.js
npm start

```

# An example of the basic structure of a folder
- `source` TypeScript contains your source files. The subfolders contain information about what you can do
    - `bot` may contain appropriate files for the telegram bot
        - `menu` bot information, including the menu shown in / start
- `dist` contains transplanted JavaScript files.

# Improvement
Do you think something is missing? Feel free to add. Then everyone can learn it easier than before :)