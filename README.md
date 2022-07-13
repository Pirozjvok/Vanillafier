# Vanillafier
Vanillafier provides a quick way to disable most of TShock's protection mechanisms, allowing your users to play without restrictions.

**Use at your own risk. This plugin will allow users to destroy your entire world.**

## What it does:
* Creates a new group 'Vanillafied'
* Moves all users (except superadmins) to the Vanillafied group
* Updates your TShock config file so that new users & guest users will be added to the Vanillafied group & new settings
```
"SpawnProtection": false,
"AnnounceSave": false,
"DisableTombstones": false,
"EnableChatAboveHeads": true,
"TileKillThreshold": 200,
"TilePlaceThreshold": 200,
"TileLiquidThreshold": 200,
"ProjectileThreshold": 200,
"HealOtherThreshold": 200,
"TilePaintThreshold": 200,
"MaxDamage": 10000,
"MaxProjDamage": 10000,
"AllowIce": true,
"AllowCutTilesAndBreakables": true,
```

The plugin does not include a way to reverse this process.

## How to use it:
1. Install the plugin
2. Run the 'vanillafy' command
3. Read the output message and confirm that you do actually want to do this:
![confirmation](https://i.imgur.com/wFUpgeF.png)
4. Complete
