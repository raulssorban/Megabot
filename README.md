![Logo](https://i.imgur.com/WC1ozTl.png)

A very extensive Discord bot launcher and manager.

## Idea
I love automating my development environment, so I decided to write something very extensive and easy to create Bots and bot Mods and execute them very easily and fast. There is also support for game mods.

## Usage
1. Create a folder "Plugins" in the root folder of the launcher and put in the bots along with the mods. Currently the bot assemblies need to speak to mods that are referenced (for initialization) in the same folder.
1. Launch the launcher and be sure the loader loaded assemblies properly, just by checking the counts. Each bot has an ID which is used to can call a named bot to launch when executing ``start <your_bot_id>`` in the console.
1. Add your bot application token, by using ``-token <your_app_token>`` in the console.
You can do all this fast by creating a shortcut of the launcher and at the end of the Target, add the lines accordingly. (e.g ``Megabot.exe -token <token> -start <bot_id>``)

For more informations, read the Wikis of this repository.
[PTGen.exe](https://github.com/raulssorban/Megabot/wiki/PTGen.exe-(Plugin-Template-Generator)) 

## Known Issues
The project is quite large and the error handling isn't the best. Most common Discord .NET issues that I've been occurring are handled appropriately and keeps the bot alive. At the time, it isn't recommended to use the application for bots in huge Discord servers - still working on optimizing execution and multiple guild support (for now, it is best recommended having the bot working on 1-2 different servers.

## License
I'm applying the GNU (General Public License) as described [here](https://raw.githubusercontent.com/raulssorban/Megabot/master/LICENSE).
