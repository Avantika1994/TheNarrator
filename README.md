# This is a full functional discord bot, Intended to bring Roleplaying Capabilities in your server.

To Use:
- create a new `.env` file based on `template.env`, fill in your credentials and endpoint. That file MUST be named `.env`
Then invite the bot into your discord server, and enable it on all desired channels with `/botwhitelist @YourBotName` in each channel.

Admin Commands:
```
/botwhitelist @YourBotName - Whitelist the bot from a channel
/botblacklist @YourBotName - Blacklist the bot from a channel
/botmaxlen [integer] @YourBotName - Set output max length
/botidletime [integer] @YourBotName - Set number of seconds before bot enters idle mode
/botfilteron @YourBotName - Enables the image prompt filter
/botfilteroff @YourBotName - Disables the image prompt filter
/botmemory @YourBotName [prompt] - Overrides the bot memory for this channel
/botbackend @YourBotName [kcpp_base_url] - Overrides the kcpp backend used by the bot in a channel
/botsavesettings @YourBotName - Saves whitelisted channels and bot memories to disk. Does not save chat history.
/botwiadd @YourBotName [key] {info} - Saves a world info entry in our database. 
/botwiremove @YourBotName key - Removes a world info entry. key is case sensitive.
/botdescribe @YourBotName - Describes an image uploaded by a user.
```

General Commands:
```
/botsleep @YourBotName - Immediately goes to sleep
/botreset @YourBotName - Clears all past context and goes to sleep
/botstatus @YourBotName - Prints current bot status
/botdraw @YourBotName [prompt] - Generates an image with a prompt
```