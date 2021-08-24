# Minecraft-Mod-Installer
i make a miecarft mod installer(it's only for windows)

the installer works in windows 7 - 10

it's writed in a .bat file and it's make easier to install minecraft mods

How it works:first when you start it create a folder in the documents which is called Mods_To_Install then it asks you if you want to install all the mods which is in the folder and to make sure that THERE IS ONLY MINECRAFT MODS and finally it moves all the mods to the minecraft mod folder if there isn't one it will create one


the code in the bat file:
@echo off
cd %userprofile%\Documents
mkdir Mods_To_Install
cd %userprofile%\Documents\Mods_To_Install
echo Are you sure want to install all mods is in the mod folder Warning:the folder there must be only minecraft mod files
pause 
cd %userprofile%\appdata\Roaming\.minecraft
mkdir mods
cd %userprofile%\Documents
copy * %userprofile%\appdata\Roaming\.minecraft\mods
ping 1.1.1.1 > NUL
