# quake2_rpgmod
A Quake 2 mod inspired by Morrowind and other RPG's for IT 266 Game Mod Development
- Added/changed controls:
    - F: Stow/Draw Weapon
    - J: Show/Hide Journal
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
        - BFG > Open Lock Spell
    - Weapons rely on stats for hitting as well as damage.

- New Systems:
    - Fatigue: This is your characters stamina and it affects all of your actions. If your character has low fatigue you will miss more swings or fail more casts. This regenerates over time.
    - Magicka: A resource used to cast spells, is spent regardless of success or failure. Does not regenerate over time.
    - Inventory: Holds your items and armor.
    - Armor: Equippable protection that gives both stats and resistance to damage.
    - Potions: Items you can use to inflict status effects on yourself
    - Statuses: Good or bad effects that last for a number of seconds.

- Stats:
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
    - Boots: Armor piece that 
