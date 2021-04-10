# Minecraft-Mod-Installer
i make a miecarft mod installer(it's only for windows)

the installer works in windows 7 - 10

it's writed in a .bat file and it's make easier to install minecraft mods

How it works:

first it's crates a folder in Documents which the folder is called Mods_To_Install

then it moves everything in the folder(make sure the folder is have only minecraft mods) in the minecraft mods directory


the code in the bat file:
echo off
cd C:\Users\yourusername\Documents
mkdir Mods_To_Install
cd C:\Users\yourusername\Documents\Mods_To_Install
echo Are you sure want to install all mods is in the mod folder Warning:the folder there must be only minecraft mod files
pause
copy * C:\Users\yourusername\appdata\Roaming\.minecraft\mods
pause



Note:for the installer to work you must edit it and replace the yourusername with your windows username (i don't mean that shows you in the welcome screen that you can see in the user folder is in C:\users)
