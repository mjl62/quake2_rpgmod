# Quake 2 RPG Mod by Matthew LiDonni
A Quake 2 mod inspired by Morrowind and other RPG's for IT 266 Game Mod Development

## I HAVE NOT TESTED THIS SINCE THE REMASTER UPDATE, BUT IT *SHOULD* STILL WORK ON THE OLDER VERSION

- To Install:
    - Take all files here and put into your Quake 2 directory in a folder called "mod" (Or whatever you like, but you MUST use that same name when in the console later)
        - Heirarchy should be: C:\...\...\steamapps\Quake 2\mod\(game .dll and other mod contents)
    - Launch Quake 2
    - From the main menu, press the ~ key to open the console and type "game mod" (or whatever you named your folder)
    - Game will reload, then launch a new game (easy recommended because you start off with horrible stats)

- Added/changed controls:
    - F: Stow/Draw Weapon
    - J: Show/Hide Journal
    - H: Show Help
    - K: Show/Hide Stats
    - L: Level up Screen
    - I: Inventory
        - Up/Down Arrow: Navigate Inventory
        - Right Arrow: Use selected item

- Weapon Changes:
    - Melee weapons (Agility/Str)
        - Blaster > Bow
        - Shotgun > Shortsword
        - SuperShotgun > Great Axe
        - MachineGun > Dagger
        - Chaingun > Great Hammer
    - Spells (Will/Int)
        - Grenade Launcher > Healing Word Spell
        - Rocket Launcher > Fireball Spell
        - Hyperblaster > Dire Viper Spell
        - Railgun > Fortify Resistance Spell
        - BFG > Open Lock Spell (Broken)
    - Weapons rely on stats for hitting as well as damage.

- New Systems:
    - Fatigue: This is your characters stamina and it affects all of your actions. If your character has low fatigue you will miss more swings or fail more casts. This regenerates over time.
    - Magicka: A resource used to cast spells, is spent regardless of success or failure. Does not regenerate over time.
    - Inventory: Holds your items and armor.
    - Armor: Equippable protection that gives both stats and resistance to damage.
    - Potions: Items you can use to inflict status effects on yourself
    - Statuses: Good or bad effects that last for a number of seconds.
    - Quests: Some NPCs upon interaction will offer a quest, adding it to your quest journal. Completing the quest requirements and returning to the quest NPC will give XP and item rewards.
    - Hitrate: Your attempts to swing a weapon or cast a spell are not guaranteed, but practicing a skill will increase that chance. Fatigue plays a big part in all your rolls, so if your character is fatigued you might want to retreat or drink a fatigue potion.

- Stats:
    - Stats can be increased by spending points, you start with 8 and gain 3 per level.
    - Strength: Increases your melee damage and max fatigue.
    - Agility: Increases your melee hitrate and max fatigue.
    - Intelligence: Increases your spell damage and max magicka.
    - Willpower: Increases your spell hitrate and max fatigue.
    - Endurance: Increases your max fatigue and max health.

- Skills:
    - As you use a weapon or spell, you gain experience in that type of skill. The more you use it, the better you get with it, increasing your hitrate in that skill area.
    - Blades: For sword and dagger.
    - Two Handed: For great axe and great hammer.
    - Bow: For the bow.
    - Destruction: For fireball and dire viper.
    - Restoration: For healing word and fortify resistance.
    - Alteration: For open lock.

- Items:
    - Health Potion: Restores Health for a few seconds.
    - Fatigue Potion: Restores Fatigue for a few seconds.
    - Magicka Potion: Restores Magicka for a few seconds.
    - Jump Potion: Increases jump height for a few seconds.
    - Fortify Potion: Increases your resistance to damage.
    - Helmet: Armor piece with an enchantment that lowers magicka cost for spells.
    - Chestplate: Armor piece with an enchantment that raises fatigue regeneration.
    - Boots: Armor piece that increases your movement speed.
