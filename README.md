# discord-life-logger
logging life events by updating the discord rich presence 

# poc
1. install DiscordConsole (https://github.com/discordconsole-team/DiscordConsole/)
2. run commands like this to update discord status on the BE
```./DiscordConsole -t "user my_user_token_here" -x "playing life walkingoutside"```
3. create basic FE that sends a request to the BE with text to use for new status (would replace the above "walking outside" text with something else, could also update the "life" part too)
4. display current status on FE app
