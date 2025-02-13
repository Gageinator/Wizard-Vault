DefaultEngine.ini should replace the file in the Config folder

steam_appid.txt goes here: Binaries->Win64

Plugins folder should be dropped into the project directory with the other folders.

---------------------------------------------------------------------------------------------
The blueprints use the default BP_ThirdPersonGameMode but can easily be changed.

You'll need to change the starting level to LoadInLevel and the editor starting level to Lobbylevel or whatever level you are using.
---------------------------------------------------------------------------------------------

You'll need to download the Plugins from this website: https://vreue4.com/advanced-sessions-binaries 
and put them in a folder name Plugins in the same folder as the project file.

Example: WizardsVault->Plugins->...