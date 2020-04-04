# Minecraft Base Hacked Client 1.8.8 (with Optifine)

## Welcome!
We have a FAQ (Q&A) section! If you are interested you can click [here](https://github.com/OxideWaveLength/Minecraft-Hack-BaseClient/wiki/FAQ-(Q&A))

We also have a Discord server! Click [here](https://discord.gg/pDweRGz) to join

If you don't have Discord, but have Twitter and need help or want to stay updated, you can follow me [here](https://twitter.com/OxideWaveLength)

------------

### Setup

#### What's needed
- Internet connection
- At least 4gb of ram
- Java JDK (1.8)
- Java JRE (1.8)
- An IDE (The setup is for Eclipse, but MCP can also be setup on [IntelliJ Idea](https://lmgtfy.com/?q=How+to+setup+Minecraft+Coders+Pack+in+IntelliJ+Idea))

#### Video!
Now a [video](https://www.youtube.com/watch?v=MIMqi82yzbQ) is available, showing how to set up the client

#### Let's get started
_Note: the instructions in italics apply ONLY to Eclipse, if you have a different IDE, [search how to set the project up on Google](https://lmgtfy.com/?q=How+to+setup+Minecraft+Coders+Pack+in+%5BMY+IDE%5D)_

- Decompile the [Minecraft Coders Pack 918 (1.8.8)](http://www.modcoderpack.com/files/mcp918.zip) _(or MCP)_ in a folder (it might take a few minutes)
- Download the project as ZIP
- Enter the folder where you decompiled the MCP in
- Enter the "src" folder
- Delete the "minecraft" folder
- Copy the ZIP's "minecraft" folder into the "src" folder
- _Launch Eclipse into the "eclipse" folder (that is inside the folder you decompiled the MCP in) as workspace_
- Optionally delete the Server project (it is safe to do so)
- _Optionally enable the @formatting tags (Window -> Preferences -> Java -> Code Style -> Formatter -> Edit -> Expand "Off/On tags" -> Tick the "Enable Off/On tags" -> Change the Profile Name (or you will not be able to save) -> OK -> Apply and Close)_
- Change the JRE version from JRE1\_6 to JRE1\_8 _(Right click on "Client" -> Build Path -> Libraries -> Scroll to the bottom -> Double click "JRE System" -> Choose a JRE1\_8 -> Finish -> Apply and Close)_

------------

### Features

- CommandManager (with four commands, "irc", "set", "help", "bind" (added in the commit #41 / 0be34e4), "friend" and "names" (both added in the commit #78 / aa78114)
- ModuleManager (with module settings, four example module (Fly, TestModule, Friends and NameProtect) and the "AdvancedTabGUI" module)
- [EventManager](https://github.com/OxideWaveLength/Minecraft-Hack-BaseClient/wiki/EventManager)
- FileManager
- ConfigManager
- [TabGUI](https://github.com/OxideWaveLength/Minecraft-Hack-BaseClient/wiki/Tab-GUI)
- [Module ArrayList](https://github.com/OxideWaveLength/Minecraft-Hack-BaseClient/wiki/Modules-ArrayList-(or-%22ToggledModules%22))
- [Hotbar Overlay](https://github.com/OxideWaveLength/Minecraft-Hack-BaseClient/wiki/Hotbar-Overlay)
- Alt Manager (By Russian412)
- Slick's FontManager (Edited by Russian412 and me) - Updated in the commit #77 / a0bfdf7
- IRC Client
- FriendsManager - manages friends and enemies. Added in the commit #95 / d5e1270 by [@evrec](https://github.com/evrec)
- ClickGui - This is not completely finished yet, but it's working and will be completed in the future. Added in the commit #112 / 0cded5b

------------

### Coming Soon / TODO

- ~~Better hotbar overlay~~ (Added in commit #44 / 7634127)
- ~~Better module arraylist~~ (Added in commit #29 / 070586b!)
- ~~Better font manager~~ (Added in commit #77 / a0bfdf7)
- ~~Help command~~ (Done)
- ~~Better FileManager / ConfigManager~~ (Not needed as of now)
- Enhance some code
- Multi Versioning! Exactly, joining 1.12 servers in 1.8.8...

------------

### Most Important TODOs

- Create a wiki for every part of the client
- ~~Finish all of the event handlers~~ (Done! Added in the commit #38 / a2c72e1)
- ~~Finish the TabGui, so that the module settings can be changed from there (they can be seen already, but not changed)~~ (Done, added in the commit #55 / 26c5f09)

------------

##### Any help is highly appreciated, I cannot put all of my time into this project, but expect updates to be coming pretty soon
