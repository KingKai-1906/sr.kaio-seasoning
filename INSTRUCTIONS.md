## 1 - Introduction  
  My idea was just to put my personal touch within this truly majestic guide called The Phoenix Flavour. I don't intend to change the core *Vanilla+* approach beneath it, but just paint it with my own colors instead.
  
  Most changes were made on the INTERFACE section, since I'm a defender of the "functionallity over aesthetics" motto, and as some mods are very nice on the aesthetics side, they miss on the other one.

  I'm also a lover of ENB lights on objects, so I'll probably add a lot of them over the time.

  I intend to make this seasoning up-to-date with the main TPF guide, and also making adjustiments when I see fit.

## 2 - Compatibility Notes  
  Since this is just a "seasoning" of ***The Phoenix Flavour***, I've tried my best to keep it all concise.
  All mods were personally checked and the few relevant conflicts, are resolved in a separate patch.

  Apart from that, no other compatibility issues reagarding the original TPF.

  With the release of TPF 4.5, Phoenix added her own addon called **The Phoenix Flavour - Extended** or shortly, **TPF-X**. I'm basing my seasoning on TPF-X from now on, since it's easier and more convenient for you users :)

## 3 - Prerequisites
  - Skyrim Special Edition with the 3 DLCs
  - **100% UNTOUCHED** version of **The Phoenix Flavour 4.5.1**, installed either manually or via Wabbajack  
  - **100% UNTOUCHED** version of **TPF-X Addon**, installed manually.

## 4 - Setup
  - **Profile Creation:**  
    - On MO2, click on the **Profiles** dropdown menu and select `<Manage...>`.  
    - At the new window, select `The Phoenix Flavour - Extended` profile and click `Copy` and name it `Sr. Kaio Seasoning`, and then click `Close`.  
    - Back at MO2 main window, click on the dropdown menu again, and select the newly created profile.
    
  >**WARNING: LEAVE THE ORIGINAL `The Phoenix Flavour` and `The Phoenix Flavour - Extended` PROFILES UNTOUCHED!**  
  
  The instructions here are meant to keep the original profiles intact and I'm not responsible if you mess up your original TPF or TPF-X installation.

## 5 - Mod List

  ### 5.1 - Disable Mods  
  Firstly, we're going to **disable** some mods that came with TPF and TPF-X. Don't delete them, because it'd break the original TPF and TPF-X profiles, just disable them by clicking the checkbox at the left side of their names, and making sure they don't have a checkmark anymore.

  Since we're based on TPF-X now, some mods are already disabled, just keep them disabled, we're not re-enabling any mods that TPF-X disabled.

  ### INTERFACE
  - [ ] **A Matter of Time - Phoenix Preset**  
    Will be replaced by a preset made by me, sorry Phoenix, mine is way way better :P
  - [ ] **Roboto Font Replacer**  
    The font itself is good, but doesn't fit Skyrim at all, I'd rather play with the vanilla font. But we'll be using Sovngarde Light as a replacer, that fits so much better in my opinion.
  - [ ] **DRELDYN's Original Main Menu Overhaul**  
    The menu itself is AWESOME, I just wanted to change it to something more like myself :)

  ### MISC STRUCTURES
  - [ ] **Skyrim 3D Signs**  
    Those models are uncompatible with the **WiZkiD Signs** that we're going to install.
    
  ### VALUABLE ITEMS
  - [ ] **Septim HD**  
    We're installing a texture I personally like more.
    
  ### APPEARANCE
  - [ ] **Vanilla Body with UNP Textures**  
  - [ ] **Cathedral Player and NPC Overhaul - Female Skin Textures**  
  - [ ] **SkySight Skins**  
  - [ ] **SkySight Skins - Shoe Fixes (Less Shine)**  
  - [ ] **Males of Skyrim - High Poly Hands**  
    We're installing new body replacers and textures that I like much more, so these mods should be disabled.

  ### ASSORTED PLUGINS
  - [ ] **No Attack Messages**  
    This one will be disabled by the same idea as the Immersive Lockpicking/Bookreading, it removes informational elements from the HUD.
  - [ ] **Disable Follower Collision**  
    Although it's nice to don't have your way blocked by your followers, unfortunately it adds a lot of clipping issues and bad follower positioning, so, this one is going out!
    
  ### TPF-X - INTERFACE
  - [ ] **Main Menu Design Replacer - Multilanguage - 60 FPS**  
    Although the idea of the mod is nice, it has tw issues: it doesn't fits well with my menu replacer and it's not properly centralized, so we're going to keep the vanilla right-side main menu.
  - [ ] **QuickLootRE**
  - [ ] **No Lockpick Activate (SKSE) - Updated**
  - [ ] **QuickLoot Retexture**  
    I personally don't like QuickLoot, so I'm disabling it
    
    If you followed TPF-X 100% (as you SHOULD), there should be a last mod on this spearator, a main font replacer that you've chose between Sovngarde and Fertigo. My Conflict Resolution Patch assumes you're using Sovngarde Light. IF you use other main font, you'll need to properly edit the `fontconfig.txt` inside it to match your font of choice. If you're using Sovngarde Light, you're covered :)
    
  ### TPF-X - GAMEPLAY TWEAKS
  - [ ] **Blade and Bunt - Vanilla Difficulty Modifiers**
  - [ ] **Blade and Blunt - Timed Block Module**  
    Those two mods make the game a lot more easier. In my humble opinion, TPF found the sweet-spot reagrding balance on difficulty and I intend to leave it that way.
  
  ### TPF-X - MISCELLANEOUS
  - [ ] **All No Tails**  
    No animals were harmed on the making of this guide :P  

  ### PATCHER OUTPUT  
  We'll need to re-run the Nemesis patcher, because we're adding a Stagger Fix mod, so before anything, disable the original one from TPF, and also rename it adding a **TPF** before, **Nemesis Output** becomes **TPF Nemesis Output**.  
  Also, we're going to regenerate the facegens, so disable its output also.  
  - [ ] **Facegen Output**
  - [ ] **Nemesis Output**

  ### 5.2 - Install Mods
  Now, we're going to add mods into some sections. I'll just list the mod sections where mods are being added, otherwise, they're 100% identical as TPF-X, so leave them UNTOUCHED.

  Every downloaded mod must be installed, activated and put under the corresponding separator as the last ones, **UNLESS NOTED OTHERWISE**!
 
  ### ESSENTIAL MODS  
  - #### [Assorted mesh fixes](https://www.nexusmods.com/skyrimspecialedition/mods/32117) - Author: *wankingSkeever*  
    **Download:** Main Files > Assorted mesh fixes - 0.15  
    **WARNING:** This mod should be placed DIRECTLY below **Unofficial Skyrim Special Edition Patch**, not at the end of separator, we don't want to overwrite **Skyrim Particle Patch for ENB**.
    
  ### FIXES
  - #### [Freed Prisoner Uses Items](https://www.nexusmods.com/skyrimspecialedition/mods/22152) - Author: *Parapets*  
    **Download:** Main Files > Freed Prisoner Uses Items - 1.0
  - #### [Falkreath Bandit Bridge - dead bandits don't trigger trap](https://www.nexusmods.com/skyrimspecialedition/mods/38477) - Author: *wankingSkeever*  
    **Download:** Main Files > Falkreath Bandit Bridge - dead bandits don't trigger trap - 0.1
  - #### [No More Random Guild Thieves](https://www.nexusmods.com/skyrimspecialedition/mods/21570) - Author: *PxR - saqk*  
    **Download:** Main Files > No More Random Guild Thieves - 1.0    
    
  ### TWEAKS
  - #### [NPC Name Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/20451) - Author: *SF117*  
    **Download:** Main Files > NPC Name Tweaks - 1.02
  - #### [Solitude Catacombs Tweak](https://www.nexusmods.com/skyrimspecialedition/mods/46699) - Author: *AndrealphusVIII*  
    **Download:** Main Files > Andrealphus' Tweaks - Solitude Catacombs - 1.0
  - #### [No Force for Illusion Spells](https://www.nexusmods.com/skyrimspecialedition/mods/38700) - Author: *WankingSkeever*  
    **Download:** Main Files > No Force for Illusion Spells - 0.1
 
  ### INTERFACE  
  - #### [A Matter of Time - Sr. Kaio Preset](https://www.nexusmods.com/skyrimspecialedition/mods/45785) - Author: *Sr. Kaio*  
    **Download:** Main Files > Sr. Kaio Preset - 1.0
  - #### [Alternate Conversation Camera Plus](https://www.nexusmods.com/skyrimspecialedition/mods/40722) - Author: *ciathyza*  
    **Download:** Main Files > Alternate Conversation Camera Plus - 2.4.6  
    After Installing, right click on mod and choose `Open in Explorer`, then navigate `SKSE > Plugins`, open
    `AlternateConversationCamera.ini` and make sure to properly set these settings:  
      - `bForceFirstPerson=0`
      - `bForceThirdPerson=0`
      - `bLetterBox=0`
  - #### [Pastel SkyUI Markers](https://www.nexusmods.com/skyrimspecialedition/mods/13604) - Author: *iTitoMix*  
    **Download:** Main Files > Pastel SkyUI SkyHUD - 5.2.PASTEL
  - #### [Undiscovered Means Unknown](https://www.nexusmods.com/skyrimspecialedition/mods/9762) - Author: *Brin_aSair*  
    **Download:** Main Files > Undiscovered Means Unknown - Compass and Map Markers - 2.11  
    FOMOD Instructions:  
    - Page 1
      - Only the Compass
      - Yes
    - Page 2
      - Yes
      - SkyHUD
    - Page 3
      - Pastel Map Markers
    - Page 4
      - Yes
    - Page 5
      - Nothing (an Invisible Icon)
  - #### [Extended UI for CHADD UPL](https://www.nexusmods.com/skyrimspecialedition/mods/44643) - Author: *Cheshyr*  
    **Download:** Main Files > Extended UI for Skyrim Uncapper Adamant Arena - 1.0.2
  - #### [Main Menu Wallpaper](https://www.nexusmods.com/skyrimspecialedition/mods/1178) - Author: *Hellstorm102*  
    **Download:** Optional Files > Main Menu Wallpaper - Book Cover - 1.0
  - #### [FiraCode for Console UI](https://www.nexusmods.com/skyrimspecialedition/mods/12387) - Author: *Hellstorm102*  
    **Download:** Main Files > Fira Code for Skyrim SE - A

  ### VISUAL FX
  - #### [FleshFX](https://www.nexusmods.com/skyrimspecialedition/mods/27456) - Author: *Deserter X*
    **Download:** Main Files > FleshFX - 1.1
  
  ### ARCHITECTURE
  - #### [WiZkiD Signs](https://www.nexusmods.com/skyrimspecialedition/mods/30481) - Author: *WiZkiD*
    **Download:** Main Files > WiZkiD Signs - 2.3  
    FOMOD Instructions:  
    - Page 1
      - WiZkiD Signs for Lanterns Of Skyrim II users
    - Page 2
      - Leave all UNCKECKED
  
  ### MISC STRUCTURES
  - #### [My Road Signs are Beautiful - Multilingual HD Retexture - SE](https://www.nexusmods.com/skyrimspecialedition/mods/46564) - Author: *Chiinami*
    **Download:** Main Files > 01 My Road Signs are Beautiful - English Version - SE - 1.2EN  
    FOMOD Instructions:  
    - Page 1
      - Weathered version - 2K-1K
      - None
      - None
    - Page 2
      - Click Install :P
  
  ### DUNGEONS
  - #### [Improved Dwemer Glass](https://www.nexusmods.com/skyrimspecialedition/mods/44553) - Author: *cunny1975*
    **Download:** Main Files > Improved Dwemer Glass - 1.1
    
  ### CLUTTER
  - #### [Rally's Civil War Document Tubes](https://www.nexusmods.com/skyrimspecialedition/mods/47637) - Author: *Rallyeator*
    **Download:** Main Files > Rally's Civil War Document Tubes - 1.2  
    FOMOD Instructions:  
    - Page 1
      - Lore Version
    - Page 2
      - Gimme that!

  ### VALUABLE ITEMS
  - #### [Ancient Imperial Septims](https://www.nexusmods.com/skyrimspecialedition/mods/37545) - Author: *WiZkiD*
    **Download:** Main Files > Ancient Imperial Septims - Classic Gold - 1.2
  - #### [More Vanilla Rings](https://www.nexusmods.com/skyrimspecialedition/mods/47198) - Author: *herumorgul*
    **Download:** Optional Files > Includes Leveled Lists - 1.0
  
  ### APPEARANCE
  - #### [Nordic Faces - Immersive Characters Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/40658) - Author: *The Community and deletepch*  
    Install each of the files as separate mods  
    **Download:** Optional Files > Nordic Faces - Textures and Body Meshes Only - 2.8  
    **Download:** Optional Files > Plugin for FaceGen Setup - 2.0  

    **WARNING:** These 2 mods need to be positioned right below the disabled **Males of Skyrim - High Poly Hands** on left pane, not at the end.

  - #### [Disparity and Diversity - Diversified Individual Race Textures](https://www.nexusmods.com/skyrimspecialedition/mods/43779) - Author: *HeartAttackMan*  
    Install each of the files as separate mods  
    **Download:** Optional Files > Disparity and Diversity - DIRT - ESP - 2.0  
    **Download:** Optional Files > Head Textures - 2K - 2.0  
    **Download:** Optional Files > Males of Skyrim or Nordic Faces - Default - 2K - 2.1  
    **Download:** Optional Files > UNP - Default - 2K - 2.0  

  ### GAMEPLAY OVERHAULS
  - #### [Triumvirate - Mage Archetypes](https://www.nexusmods.com/skyrimspecialedition/mods/39170) - Author: *Enai Siaion*  
    Install each of the files as separate mods  
    **Download:** Main Files > Triumvirate 1.7.0 - 1.7.0  
    **Download:** Optional Files > Triumvirate - Adamant Compatibility Patch - 1.7.0  
    **Download:** Optional Files > Triumvirate - Mysticism Compatibility Patch - 1.6.0
    
  ### BALANCING
  - #### [Enchantments and Potions Work for NPCs - EPW4NPCs (SKSE64) (SPID Plugin ini)](https://www.nexusmods.com/skyrimspecialedition/mods/37607) - Author: *KaptainCnucklz*  
    **Download:** Main Files > Enchantments and Potions Work for NPCs - EPW4NPCs (MO2 Friendly Edition) - 1.0.1
  - #### [Slip off Slopes](https://www.nexusmods.com/skyrimspecialedition/mods/45886) - Author: *wankingSkeever*  
    **Download:** Main Files > Slip off Slopes - rag doll damage depends on difficulty - 0.4
  
  ### NEW CONTENT
  - #### [Penitus Oculatus](https://www.nexusmods.com/skyrimspecialedition/mods/21061) - Author: *TheRegisteredOne - ws - wankingSkeever*  
    **Download:** Main Files > Penitus Oculatus - 0.13.1

  ### MISCELLANEOUS  
  - #### [Pick up books simple - With weightless books option](https://www.nexusmods.com/skyrimspecialedition/mods/2453) - Author: *Alaebasta*  
    **Download:** Main Files > Pick up books simple .esp flagged as .esl - 2.0
  - #### [Reading is Good (SKSE)](https://www.nexusmods.com/skyrimspecialedition/mods/42026) - Author: *Parapets*  
    **Download:** Main Files > Reading Is Good - 1.0.4
  - #### [First Person Camera Height Fix](https://www.nexusmods.com/skyrimspecialedition/mods/28091) - Author: *Imp of the Perverse - Threepkiller*  
    **Download:** Main Files > First Person Camera Height Fix - 1.2.2
  - #### [Spell Amnesia](https://www.nexusmods.com/skyrimspecialedition/mods/4091) - Author: *Vox Sola*  
    **Download:** Main Files > Spell Amnesia - 1.0
  - #### [A Guiding Light - Clairvoyance Reimagined](https://www.nexusmods.com/skyrimspecialedition/mods/35464) - Author: *Parapets*
    **Download:** Main Files > Guiding Wisp - 2.3.2
  - #### [HearthFires - Unique Display Rooms - SSE](https://www.nexusmods.com/skyrimspecialedition/mods/4770) - Author: *Jayer117 and EdmondNoir*
    **Download:** Main Files > HearthFires - Unique Special Edition Display Room - 6.0
  - #### [Hearthfires Houses Building Fix](https://www.nexusmods.com/skyrimspecialedition/mods/27298) - Author: *Ice885*
    **Download:** Main Files > Hearthfires Houses Building Fix - 0.1
  
  ### ASSORTED PLUGINS
  - #### [Stagger Direction Fix - SSE](https://www.nexusmods.com/skyrimspecialedition/mods/43339) - Author: *Maxsu*
    **Download:** Main Files > Stagger Direction Fix-SSE V2.02a - V2.02a
  - #### [Wash That Blood Off](https://www.nexusmods.com/skyrimspecialedition/mods/27325) - Author: *powerofthree*
    **Download:** Main Files > Wash That Blood Off - SSE 1.5.97 - 1.2 - 1.2
    

  ### SKELETON & ANIMATIONS
  - #### [Supreme Dwemer Spheres](https://www.nexusmods.com/skyrimspecialedition/mods/35769) - Author: *Rougeshot*
    **Download:** Main Files > Supreme Dwemer Spheres - 1.3
  - #### [Callous Dwemer Centurions](https://www.nexusmods.com/skyrimspecialedition/mods/34395) - Author: *Rougeshot*
    **Download:** Callous Dwemer Centurions > Name - 1.1
  - #### [Dreaded Dwarven Spiders](https://www.nexusmods.com/skyrimspecialedition/mods/27047) - Author: *Rougeshot*
    **Download:** Main Files > Dreaded Dwarven Spiders - 1.0
  - #### [Hardy Hares](https://www.nexusmods.com/skyrimspecialedition/mods/27366) - Author: *Rougeshot*
    **Download:** Main Files > Hardy Hares - 1.0
  - #### [Gritty Goats](https://www.nexusmods.com/skyrimspecialedition/mods/26665) - Author: *Rougeshot*
    **Download:** Main Files > Gritty Goats - 1.1
  - #### [Honored Hounds](https://www.nexusmods.com/skyrimspecialedition/mods/25563) - Author: *Rougeshot*
    **Download:** Main Files > Honored Hounds - 1.0
  - #### [Sickening Skeevers](https://www.nexusmods.com/skyrimspecialedition/mods/24428) - Author: *Rougeshot*
    **Download:** Main Files > Sickening Skeevers - 1.0
  - #### [Bullish Bovine](https://www.nexusmods.com/skyrimspecialedition/mods/33888) - Author: *Rougeshot*
    **Download:** Main Files > Bullish Bovine - 1.0
  - #### [Heartland Horses](https://www.nexusmods.com/skyrimspecialedition/mods/22083) - Author: *Rougeshot*
    **Download:** Main Files > Heartland Horses - 1.0
  - #### [Mighty Mammoths](https://www.nexusmods.com/skyrimspecialedition/mods/24237) - Author: *Rougeshot*
    **Download:** Main Files > Mighty Mammoths - 1.0
  - #### [Immersive Smilodons](https://www.nexusmods.com/skyrimspecialedition/mods/18429) - Author: *Rougeshot*
    **Download:** Main Files > Immersive Smilodons - 1.2
  - #### [Savage Bear](https://www.nexusmods.com/skyrimspecialedition/mods/16343) - Author: *Rougeshot*
    **Download:** Main Files > Savage Bear SE - 1.1c
  - #### [Absolute Arachnophobia](https://www.nexusmods.com/skyrimspecialedition/mods/24058) - Author: *Rougeshot*
    **Download:** Main Files > Absolute Arachnophobia - 1.1
  - #### [Infamous Ice Wraiths](https://www.nexusmods.com/skyrimspecialedition/mods/29712) - Author: *Rougeshot*
    **Download:** Main Files > Infamous Ice Wraiths - 1.4
  - #### [Notorious Netches](https://www.nexusmods.com/skyrimspecialedition/mods/29323) - Author: *Rougeshot*
    **Download:** Main Files > Notorious Netches - 1.1
  - #### [Grandiose Giants](https://www.nexusmods.com/skyrimspecialedition/mods/23889) - Author: *Rougeshot*
    **Download:** Main Files > Grandiose Giants - 1.2
  - #### [Supreme Seekers](https://www.nexusmods.com/skyrimspecialedition/mods/23349) - Author: *Rougeshot*
    **Download:** Main Files > Supreme Seekers - 1.0
  - #### [Heinous Ash Hoppers](https://www.nexusmods.com/skyrimspecialedition/mods/22409) - Author: *Rougeshot*
    **Download:** Main Files > Heinous Ash Hoppers - 1.0
  - #### [Nightmare Chaurus](https://www.nexusmods.com/skyrimspecialedition/mods/21488) - Author: *Rougeshot*
    **Download:** Main Files > Nightmare Chaurus - 1.0
  - #### [Supreme Chaurus Hunters](https://www.nexusmods.com/skyrimspecialedition/mods/22263) - Author: *Rougeshot*
    **Download:** Main Files > Supreme Chaurus Hunters - 1.0
  - #### [Grave Gargoyles](https://www.nexusmods.com/skyrimspecialedition/mods/21907) - Author: *Rougeshot*
    **Download:** Main Files > Grave Gargoyles - 1.0
  - #### [Looming Lurkers](https://www.nexusmods.com/skyrimspecialedition/mods/23122) - Author: *Rougeshot*
    **Download:** Main Files > Looming Lurkers - 1.0
  - #### [Riekling Reavers](https://www.nexusmods.com/skyrimspecialedition/mods/22948) - Author: *Rougeshot*
    **Download:** Main Files > Riekling Reavers - 1.1
  - #### [Riekling Roughriders](https://www.nexusmods.com/skyrimspecialedition/mods/22765) - Author: *Rougeshot*
    **Download:** Main Files > Riekling Roughriders - 1.1
  - #### [Bristleback Boars](https://www.nexusmods.com/skyrimspecialedition/mods/22578) - Author: *Rougeshot*
    **Download:** Main Files > Bristleback Boars - 1.0
  - #### [Ultimate Combat and Creatures Behaviour compatibility for Nemesis](https://www.nexusmods.com/skyrimspecialedition/mods/45966) - Author: *NickNak*
    **Download:** Main Files > Ultimate Combat and Creature Behaviour's Nemesis Compatibility - 1.12  
    FOMOD Instructions:  
    - Page 1
      - Leave, justo go next
    - Page 2
      - Leave all UNCKECKED
  - #### [Racial Body Morphs SE - Diverse body types and height by Race and Gender](https://www.nexusmods.com/skyrimspecialedition/mods/20684) - Author: *Onholyservicebound*
    **Download:** Main Files > Racial Body Morphs 1.1 - 1.1

  ### FINAL PATCHES
  - #### [Sr. Kaio Seasoning - Conflict Resolution Patch](https://www.nexusmods.com/skyrimspecialedition/mods/46017) - Author: *Sr-Kaio*
    **Download:** Main Files > Sr. Kaio Seasoning - Conflict Resolution Patch - 4.4.2

## 6 - Finishing Up  
  - Download and apply the updated [loadorder.txt](https://raw.githubusercontent.com/caiobraz/sr.kaio-seasoning/main/loadorder.txt) (right-click > `Save link as...`),
    the same way [Phoenix does on her guide](https://thephoenixflavour.com/skyrim-se/finalisation/wrapping-up/#load-order-txt)
  - Go to TPF's [Facegen](https://thephoenixflavour.com/tpf/finalisation/facegen/) page, and start following the steps until you arrive at **Regenerating Facegen** part.  
  Use the following setup:  
  ![image](https://user-images.githubusercontent.com/6069263/114256096-229c3380-998e-11eb-8339-1c3e5a006312.png)  
  NPCsWithFaces.esp being the ACTIVE FILE  
  Then continue following Phoenix's page, when you have to create the mod from Overwrite name it **Facegen Output DD**  
  When you finish this step **DISABLE** the **NPCs With Faces** and **Plugin for FaceGen Setup** mods on left pane.

  - Go to TPF's [Nemesis Behavior Engine](https://thephoenixflavour.com/skyrim-se/finalisation/nemesis/) page, and redo all steps **BUT**
    with an additional detail: before hitting `Update engine` on Nemesis, you need to check the `Maxsu Stagger Direction Fix` checkbox.
    It is the 7th entry on the list, with priority 6, just check it.
 
## 7 - MCM Configuration
  - Go to [TPF Mod Configuration page](https://thephoenixflavour.com/skyrim-se/mod-configuration/), and follow all the steps.

  Now, apply the following additional steps
  - ### **Alchemy Adjustments**  
    **_Activate:_** Settings > Prevent fortify Alchemy/Enchanting loop
  - ### **Cathedral Weather**  
    **_Activate:_** Settings > Seasonal Perspective
  - ### **Extended UI**  
    **_Activate:_** Show attribute modifiers  
    **_Activate:_** Show skill modifiers
  - ### **Immersive HUD**  
    **_Activate:_** Options > Enable fast fade of magicka  
    **_Activate:_** Options > Enable fast fade of health  
    **_Activate:_** Options > Enable fast fade of stamina
  - ### **Lanterns of Skyrim II**  
    **_Deactivate:_** Settings > Always ON
  - ### **moreHUD**  
    **_Deactivate:_** Everything on Enemy's Level page

## 8 - Changelog  

  You can see the changelog [here](CHANGELOG.md)
