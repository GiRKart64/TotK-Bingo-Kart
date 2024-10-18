## About TotK Bingo Kart
TotK Bingo Kart is a bingo card generator for Tears of the Kingdom. Suitable for streamers.

## How to install
Just extract and run ****TotKBingo.exe****, all files required are included in the archive, as well as some non-essential files that can be deleted.

## Non-essential files
Non-essential files included are background.png, cross.png, cross-outline.png and win.png. All of these files can be deleted if you do not wish to use them. A marker image will be generated if cross.png is deleted for example. You can set your own customized bingo marker in settings, either a solid color or png image. 

## Optional files
Item images & map marker images are available in this archive: [item-images-png.7z](https://mega.nz/file/I9MxUTST#KUXysPhXE3I5gd53em8xW0AB5eqedS2TDxOQPMOcKVo), to use simply extract to your TotK Bingo Kart folder. TotK Bingo Kart will generate text based bingo cards without these item images. Map markers can be replaced in this folder with customized map markers too.

## Using TotK Bingo Kart
Using TotK Bingo Kart is pretty straight forward, simply generate a game by pressing generate button. After that click on a square to mark it as you play. There is options to include or exclude items from a game, all a checked by default. If you wish to output file for OBS (either image or HTML) you can specify it in settings, save locations are set to TotK Bingo Kart directory by default but will not be generated until the boxes are checked.

## Saving and loading games
Pretty simple. Save a game if you want to use it again or send it to someone to compete with and load a game you want to continue or someone has sent you.

## Map
Can show or hide map. Map will show markers for locations (shrines, lightroots & skyview towers), overworld bosses, bosses, armor and monster forces. 

## Settings
There is many options in settings to customise bingo cards. Font, size, color etc. Also number marker, position, relative size and outline. You can set your own custom marker here too.

## Discord integration ([cURL required]( https://curl.se/windows/))
You can send TotK Bingo game files or a text based list with TotK Object Map links to your Discord channel by putting [cURL]( https://curl.se/windows/) in TotK Bingo Kart folder then creating a webhook in Discord and pasting link into Webhook URL on Discord tab in settings. Twitch user name is optional.

## Future development
* More accurate TotK Object Map links location links for some items for Discord list (by hash rather than text search)
* Improved HTML generation, it is more limited compared to image generation for now
* Feature to exclude specific items like pristine weapons and amiibo items etc.
* Feature to exclude items based on map, so limit items to surface map for example.
* Migrate project to C#
