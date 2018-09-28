# Megabot
A very extensive Discord bot launcher and manager.

## Idea
I love automating my development environment, so I decided to write something very extensive and easy to create Bots and bot Mods and execute them very easily and fast. There is also support for game mods.

## Usage
Create a folder "Bots" in the root folder of the launcher and put in the bots along with the mods. Currently the bot assemblies need to speak to mods that are referenced (for initialization) in the same folder.
Once done with that, launch the launcher and be sure the loader loaded assemblies properly, just by checking the counts. Each bot has an ID which is used to can call a named bot to launch when executing "start <your_bot_id>" in the console.
Before starting the bot you need to add your bot application token, by using "-token <your_app_token>" in the console.
You can do all this fast by creating a shortcut of the launcher and at the end of the Target, add the lines accordingly. (e.g "Megabot.Launcher.exe -token <token> -start <bot_id>")