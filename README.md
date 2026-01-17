# StatusBot-Hytale-Discord-Plugin-
StatusBot is a Hytale server plugin that connects your server to Discord and dynamically updates the bot’s status with the current player count.


<img width="223" height="95" alt="startingBOT" src="https://github.com/user-attachments/assets/fb073058-1d7f-4d2f-af5f-9c8a32b528ae" />
<img width="236" height="94" alt="Screenshot 2026-01-17 093618" src="https://github.com/user-attachments/assets/795fa902-0ad8-43b3-8fa8-c6f635e65600" />



✨ Features

Live player count tracking using official Hytale player events

Discord bot presence updates (e.g. “Playing with 12 players”)

Startup status message (e.g. “Server starting…”)

Fully configurable update interval and status message


🤖 Creating the Discord Bot
Go to the Discord Developer Portal
https://discord.com/developers/applications

Click “New Application” and give it a name.
Open the application → Bot tab
Click “Add Bot”
Choose a profile icon and name
Copy the Bot Token (keep this secret!)
Enable Presence Intent and Server member intent
Go to "OAuth2"
Enable "Bot and administrator" 
Go to the bottom and copy the link and paste it in your browser to invite it to your server.

⚠️ Do not share your bot token.
Anyone with this token can fully control your bot.

Install "StatusBotByBanan.jar and paste it in your mods folder
A new config file will be generated in the same folder where you can change the following:
{
  "discordToken": "",
  "statusMessage": "Playing with {online} players!",
  "updateIntervalSeconds": 60
}

UpdateInterval SHOULD NOT BE LESS THAN 30, AS DISCORD CAN RATE LIMIT YOU.
