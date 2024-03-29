# RotMG-RPC
UNOFFICIAL Discord Rich Presence for Realm of the Mad God Exalt. (Only available for: Windows)

Made with <3 by Neruncio & neopkr.

[Submit your profile for us to grab your realmeye skins here!](https://forms.office.com/r/JEgK55YLCL)

 _New link for the skins, previous link got deleted_

# Screenshots
![Knight](https://www.latenightprogrammers.com/src/assets/RotMGRPC/neopkrKnight.jpg)
![MysticESP](https://www.latenightprogrammers.com/src/assets/RotMGRPC/neopkrMystic.jpg)
![PenguinKnight](https://www.latenightprogrammers.com/src/assets/RotMGRPC/neruncioKnight.jpg)
![Default Bard Skin](https://www.latenightprogrammers.com/src/assets/RotMGRPC/neopkrBard.jpg)

_We need screenshots using the RPC! Send message on RotMG to: neopkr or Neruncio if you want to send your screenshot!_

<details>
<summary>How it works</summary>
<br>

-This Rich Presence does not get involved with the game's code, instead, it takes info directly from RealmEye. The page is scrapped, which lets us take (non malicious) information we need, such as: Current character, base fame & level.

- Due to RealmEye is not longer supported with RotMG API the content retrieve for discord status maybe took a while to update.
</details>

<details>
<summary>List of currently available skins</summary>
<br>

#### General
    - Exalted Skins

#### Rogue
    - Mushroom Girl Rogue
    - Jack the Ripper
    - Cloaked Ascendant Rogue
    - Brigand
    - Turkey Rogue
#### Archer
    - Blorph the Archer
    - Elven Archer
    - Kings Bowman Archer
    - Robin Hood
    - Sunflower Archer
#### Wizard
    - Snow Queen
    - Hermit Wizard
    - Ordinary Magician
    - Little Evil Doer Wizard
    - Duality Wizard
#### Priest
    - Ice King Priest
    - Lyrical Priestess
    - Carthusian Monk Priest
    - Shrine Priestess
    - Antinomy Priest
#### Warrior
    - Chinese Princess Warrior
    - Explorer
    - Unicorn Warrior
    - Lodestar Warrior
#### Knight
    - Sleepover Knight
    - Heroic Knight
    - Astronaut Knight
    - Glacius Knight
    - Bear Suit Knight
    - Penguin Knight
#### Paladin
    - Cleaner Maid Paladin
    - Demon Spawn
    - Mini Royal Gladiator Paladin
    - Holy Avenger
#### Assassin
    - Blue Frog Assassin
    - Vampire Hunter
    - Alice Assassin
    - Sweet Chocolatier Assassin
    - Veteran Assassin
    - Snowball Kid Assassin
    - Cronus Entity Assassin
#### Necromancer
    - Anubis Necromancer
    - Necro of Christmas Yet-to-Come
    - Hollow Prince Necromancer
    - Vampire Lord
    - Vengeful Yokai Necromancer
#### Huntress
    - Nexus No Miko
    - Forest Tracker Huntress
    - Mini Queen Bee Huntress
    - Mini Thessal
    - Night Huntress
#### Mystic
    - Leprechaun Mystic
    - Yuki Onna Mystic
    - Lil' Bo-Peep
    - Lil Red
    - Lunar Mystic
    - Aphrodite Mystic
    - Hula Mystic
    - Stone Mystic
#### Trickster
    - Queen of Misrule Trickster
    - Chinese Dress Trickster
    - Bunny Trickster
    - Traffic Cone Trickster
    - Jiangshi Trickster
    - Village Peasant Trickster
#### Sorcerer
    - Mini Court Magician Sorcerer
    - Mini Malus Sorcerer
    - Blizzard Sorcerer
#### Ninja
    - Wind Flower Ninja
    - Death
    - Slashing Beauty
    - Baby Djinja
    - Kabuki Ninja
#### Samurai
    - Oryxmas Samurai
    - Antinomy Samurai
    - Fire Flower Samurai
#### Bard
    - Twintailed Vocalist Bard
    - Antinomy Bard
    - Wandering Spellcaster Bard
#### Summoner
    - Menagerie Master Summoner
    - Mauve Magus Summoner
#### Kensei
    - Mini Tidal Wave Kensei
    
</details>

<details>
<summary>Non-Supported Skins</summary>
<br>
    
#### Kensei
    - Rain Flower Kensei
    - Zodiac Tiger Kensei
#### Sorcerer
    - Fire Elemental Sorcerer
#### Huntress
    - Drill Operator Huntress
#### Summoner
    - Freyja Summoner
#### Bard
    - Mini Storm Caller Bard
    
</details>

# Errors

### Error 21: Cannot found data/database
- This error is not common and its fatal for the program. As the error said, data folder o database file are missing in the main folder.
- What is 'database' file?: Database file is an CFG File that includes all the skins ID for the discord presence, without this file, the RPC can not set the current skin image that are using the character.
- Solution:
  1. If data folder don't exist: Create a folder inside of the RPC folder called 'data'
  2. Download: database, skin_version, rpc_version, updater_version and RPCUpdater.
  3. Paste the following files: database, skin_version, rpc_version, updater_version inside of the data folder that we create at step 1.
  4. Paste RPCUpdater on the RPC folder.
- Why i need to download RPCUpdater?: Assuming there is not data folder when this errors ocurred, there is 4 important files for program functionallity that are NOT in the folder. In specially the file ```updater_version``` is only created building the RPC, this file is not updateable. So if this file need to be changed, RPCUpdater need to be changed too.

### Error 12: Updater not found
- **IMPORTANT: If you have old version of the RPC (v3.0.0, v3.0.1) or 2022 versions, please redownload the RPC, thats versions are no longer support and contains several bugs.**
- This error is uncommon because in each build comes with the Updater. Updater not found: RPCUpdater is missing on the RPC folder.
- Solution:
 1. Check your current ```updater_version``` (located in data/ folder) and compare it with the online version: [updater_version](https://github.com/latenightprogrammers/RotMGRPC/blob/main/updater/updater_version). If versions are compatibles you can proceed with this solution.
 1.1. If ```updater_version``` are not the same, re download the RPC to the latest version [here](https://github.com/latenightprogrammers/RotMGRPC/releases).
 2. Download: [RPCUpdater](#)
 3. Paste RPCUpdater in your RPC folder
- And thats it, if the message persist, re download the RPC.
