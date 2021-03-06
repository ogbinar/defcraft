# Client - PC, MAC, or LINUX
1. go to https://tlauncher.org/
2. download for your OS ie. windows
3. input your username (in game name)

![gha](https://user-images.githubusercontent.com/9988006/83399933-9f888380-a434-11ea-9cdc-96eeff31f396.PNG)

note: to be able to change skins, register your username in tlauncher.org (pls dont use very long name)

4. select installation folder and use version 1.15.2 (or whatever is latest)
5. launch minecraft
6. select multiplayer

![server](https://user-images.githubusercontent.com/9988006/83400401-54bb3b80-a435-11ea-85e8-c68b9a091440.PNG)

7. add and connect to server 167.99.72.42 port 25565 NAME: DROP MC SERVER

# Client - Bedrock (Android and Windows 10)
1. install Minecraft on your device:
* Android - install APK 1.14 (download here: https://www.dropbox.com/s/zqo9yijdlcpnkxo/minecraft-pe-1-14-60.apk?dl=0)
* Windows 10
2. open minecraft in android
3. go to settings, profile - change your name
4. go to play, then servers click add server
5. use server 167.99.72.42 port 19133 - NAME: DROP MC SERVER

## note: this approach should work in IOS but may need additional settings in Switch and PS4 / XBOX because you can't input port there.

# Server
1. go to https://papermc.io/downloads#Paper-1.15 and download latest version of server
2. install java 8 JRE  (or latest)
3. java -Xms512M -Xmx1024M -XX:MaxPermSize=128M -jar paperclip.jar
4. configure server.properties
* preferred seed
* disable online mode
* disable whitelist (or enable, up to you)
* set yourself as op

* white list commands
Whitelist on - This activates the whitelist
Whitelist off - This disables the whitelist
Whitelist add playername - This will add a player to the whitelist
Whitelist remove playername - This will remove a player from the whitelist
Whitelist list - This will list the players who have been added to the whitelist

REFERENCE:
* https://www.vultr.com/docs/setup-paperspigot-on-ubuntu
* https://minecraft.gamepedia.com/Tutorials/Setting_up_a_server
* Setup proxy for allowing MCPE / Bedrock clients (1.14) to connect to Java Server (1.15) https://github.com/DragonetMC/DragonProxy
