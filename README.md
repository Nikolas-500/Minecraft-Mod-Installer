# Minecraft-Mod-Installer
i make a miecarft mod installer(it's only for windows)

the installer works in windows 7 - 10

it's writed in a .bat file and it's make easier to install minecraft mods

How it works:

first it's crates a folder in Documents which the folder is called Mods_To_Install

then it moves everything from the folder(make sure the folder is have only minecraft mods) to the minecraft mods directory(if there is no mods directory it will create one)


the code in the bat file:
@echo off
cd %userprofile%\Documents
mkdir Mods_To_Install
cd %userprofile%\Documents\Mods_To_Install
echo Are you sure want to install all mods is in the mod folder Warning:the folder there must be only minecraft mod files
pause 
cd %userprofile%\appdata\Roaming\.minecraft
mkdir mods
copy * %userprofile%\appdata\Roaming\.minecraft\mods
pause
