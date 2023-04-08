# AUC - Alcardian's Unlimited Clones
A mod for Dungeon Siege 1. Find the mod on Nexusmods at https://www.nexusmods.com/dungeonsiege1/mods/151

## Description
### AUC - Alcardian's unlimited clones
Removes summon limit on summon clone. I made this mod as it seems to not be included in mods removing summon limits.  
Use AUC_Plus_dsloa_<version> if you want unlimited duration as well.

### Reqirements:
* Mod requires LOA DLC. Summon clone is a LOA spell. 
* All players in multiplayer need to install this mod if you plan to use it in multiplayer. Not host only.

### Installation instructions:
* Download "**AUC_dsloa_<version>.zip**" or "**AUC_Plus_dsloa_<version>.zip**". **Not both**.
* Unzip "**AUC_dsloa_<version>.zip**"
* Copy "**AUC_dsloa_<version>.dsres**" to Resources folder

### Uninstall:
Delete "AUC_dsloa_<version>.dsres" / "AUC_dsloa_Plus_<version>.dsres" in Resources folder. No other cleanup.


## Project structure
* Source code for unlimited clones without duration change: DS1_AUC\src\AUC-Alcardian_Unlimited_Clones
* Source code for unlimited clones with infinite duration: DS1_AUC\src\AUC-Alcardian_Unlimited_Clones_Plus

## Package mod using source
* Use "TankCreator2_ds2", "TankCreator2.exe"
    * Source, select the folder containing your folder structure. Like the folder containing the "world" folder.
    * Output, name it <ModName>.dsres
    * Select Format "DS & LOA"