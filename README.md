## IDFetcherBot
A discord bot that gets user ID’s from usernames in a server, and also the other way around.

IDFetcherBot is a personal-use Discord bot that looks up user IDs, usernames, and display names based on mentions, usernames, or raw IDs. It includes both traditional !idbot commands and modern slash command support with autocomplete.



This project is licensed for personal use only. Redistribution, resale, or public hosting is not allowed. See LICENSE.txt for full terms.

#### Add to your server using the official invite link (recomended)
Just click on the link below:
https://discord.com/oauth2/authorize?client_id=1390152622069252216&permissions=277025541120&integration_type=0&scope=applications.commands+bot





Or just do a manual install as seen below (Takes longer, not recommended for beginers.


# Or

To install the bot:

Download the latest release from the releases tab.

Put the file in a known location

This bot requires Python 3.9 or later and discord.py v2.x. You can install the required discord libraries using pip after you install Python:

pip install -U discord.py

# Next

Open bot.py  in a text editor and scroll to the bottom. Replace the line in the bot.py file:

bot.run("YOUR_TOKEN_HERE")

With your actual Discord bot token in parentheses. You can get a token from the Steps below.

How to Create Your Bot in Discord and Get a Token
Go to https://discord.com/developers/applications

Click New Application, name it, and go to the Bot tab

Click Add Bot, then under Token, click Copy

Go to Bot, and check the 3 sliders under Privileged Gateway Intents

Go to OAuth2 and check:

Scopes: bot, applications.commands

Permissions: Read Messages, Send Messages, Use Slash Commands, View Members

Copy the generated link and use it to invite the bot to your server

Running the Bot


Once your token is set and dependencies are installed, enter this into python when in the directory of the files:

python bot.py

If it connects successfully, you’ll see a confirmation in your terminal and your slash commands will sync.

# Usage


Once the bot is running:

Use !idbot <mention | name | ID> in any server channel

Or use the /idbot slash command and begin typing a user’s name



Examples:

!idbot @Mention
!idbot Username
!idbot DisplayName
!idbot 123456789012345678
The bot will respond with the user’s ID, username, and display name.

## License


This project is provided for private, personal use only.

You may not redistribute, resell, publish, or host this bot publicly without written permission.



See LICENSE.txt for complete terms.
