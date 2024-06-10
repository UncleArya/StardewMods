# Changelog

## 0.4.3

-	Added workaround to spawn condition of volcano egg due to a current bug in Item Extensions

## 0.4.2

-  Updated Spanish and French translations

## 0.4.1

-   Fixed Gunther's quest so it unlocks at an appropriate time
-   Fixed issue with mail getting sent twice in multiplayer
-   Fixed instance where a 3rd egg incubator could be spawned in the Giant Coop after upgrading

## 0.4.0

-   Added new Level 3 Chickens (Aquatic, Farmer)
-   Added new Level 4 Chickens (Bomb, Monster)
-   Added new Level 5 Chickens (Artifact, Iridium, Radioactive, Volcano)
-   Created quest to obtain a Farmer Chicken Egg
-   Created quest to obtain an Artifact Chicken Egg
-   Added spawn conditions for Aquatic, Bomb, Monster, Radioactive, and Volcano Chicken Eggs
-   Added craftable Iridium Fusion Chamber
-   Added shop items for Krobus, Marnie, Willy, the Dwarf, the Desert Trader, the Volcano Shop once unlock conditions are satisfied
-   Created custom Geode Egg mining node; Geode Eggs now drop only from the custom node, not from vanilla-looking geode nodes
-   Added ability for Bait egg to also convert into Wild Bait and Deluxe Bait once conditions for obtaining those recipes have been met
-   Added config option to allow chicken sprite styles to be randomized and allow both Vanilla or Hatta style at the same time for chickens that have multiple sprite options (not all chickens do)
-   This setting only applies to new chickens, will not affect existing chickens
-   Chicken appearance options can alternatively be set to only Vanilla Style or only Hatta Style
-   Added config option to allow for Giant Coop upgrade to retain the exterior appearance of the Deluxe Coop (requires save reload if setting changed while in game)
-   Updated translations: French, Spanish, Turkish (Thank you translators!)

## 0.3.4

-   Added French language support. Thanks [Hultra00](https://next.nexusmods.com/profile/Hultra00/about-me)!
-   Added spawn condition for geode egg node in the Quarry

## 0.3.3

-   Hotfix for Manifest version

## 0.3.2

-   Added Portuguese (BR) language support. Thanks [Pontassnape](https://next.nexusmods.com/profile/pontassnape/about-me)!
-   Added additional spawn conditions for obtaining moss chicken egg
-   Slightly reduced spawn rate of custom geode nodes
-   Slightly reduced spawn rate of sap chicken egg

## 0.3.1

-   Changed resource chicken sleep sprite to correct sprite
-   Giant Coop: Moved spawn location of second incubator to spot that shouldn't conflict with previously places items or modded coops. (you can pickup and move the Second incubator when hit with a pickaxe/axe)
-   Sap Chicken: Removed sap egg from drop pool of Mahogany Tree due to game bug
-   Updated Spanish translation

## 0.3.0

-   Added new Level 2 Chickens (Bait Chicken, Sap Chicken)
-   Added new Level 3 Chickens (Iron Chicken, Quartz Chicken, Moss Chicken, Geode Chicken)
-   Added new Level 4 Chickens (Bone, Gold)
-   New custom sprites created for all chickens (Vanilla and Hatta Style) by [Tophatta](https://www.nexusmods.com/stardewvalley/users/54445652)
-   Added a upgrade to the Deluxe Coop called the Giant Coop
-   Giant Coop has a capacity of 24 coop animals and adds a second egg incubator
-   Added craftable Gold, Iron and Quartz Fusion Chambers and their recipes
-   Added [Item Extensions](https://www.nexusmods.com/stardewvalley/mods/20357) as a dependency to allow for custom node spawns
-   [Item Extensions](https://www.nexusmods.com/stardewvalley/mods/20357) and [Farm Type Manager ](https://www.nexusmods.com/stardewvalley/mods/3231) are technically not a firm requirement but if they are not installed then the Bait, Bone, Geode, and Fiber chickens are not obtainable and the Moss chicken egg forage conditions will not apply
-   Added 4 custom geode stone nodes and conditions for them to drop geode chicken eggs
-   Added custom fossil stone node and clump and conditions for them to drop bone chicken eggs
-   Added forage and drop conditions for moss chicken egg
-   Added forage condition for bait chicken egg
-   Added drop condition for sap chicken egg
-   Changed fiber egg drop condition from artifact spot to drop chance from custom weeds
-   Slightly increased forage spawn rate for fiber chicken egg
-   Greatly simplified the config options for better clarity and readability
-   Added difficulty options (easier and harder) for: amount of resources obtained from resource eggs, egg price, chicken price, days for a baby chicken to hatch, days for a baby chicken to mature, days for a chicken to produce an egg
-   Level 1 resource egg sell price defaults to the same as vanilla eggs
-   Level 1 chickens sell & purchase price defaults to double vanilla chickens (since they have double the usefulness)
-   Each subsequent increase in chicken level adds 10% to both the sell price of eggs and sell price of chickens
-   Some more advanced chickens coming in future updates may take longer to incubate, mature, and produce resource eggs to scale with rarity of resources produced
-   Combined resource egg converter processing options into a singular time for all resource eggs
-   Combined mayo machine processing options into a singular time for all resource eggs
-   Removed Progression Mode and ability to disable individual chickens, as level 1 chickens are now all required to obtain higher level chickens
-   Reorganized file & folder structure to better align with CP best practices and support future updates
-   Be sure to fully delete previous mod folder when updating, do not overwrite

## 0.2.2

-   Added Spanish language support. Thanks [LuCiiel20](https://forums.nexusmods.com/profile/11110368-luciiel20/)!

## 0.2.1

-   Added Turkish language support. Thanks [Stola90](https://forums.nexusmods.com/profile/193926774-stola90/)!

## 0.2.0

-   Added Copper Chicken
-   Added Fiber Chicken
-   Added Hardwood Chicken
-   Added category for Level 1 Chickens (Clay, Coal, Stone, Wood)
-   Added category for Level 2 Chickens (Copper, Fiber, Hardwood)
-   Added unlockable crafting recipes and corresponding items for Copper and Hardwood Egg Fusion Chambers to hatch baby copper and hardwood chickens
-   Additional copper and hardwood chickens can be hatched in the vanilla incubator using the copper and hardwood eggs those chickens lay
-   Added [Farm Type Manager (FTM)](https://www.nexusmods.com/stardewvalley/mods/3231) as a dependency to allow for forage spawning
-   Added forage spawn conditions for the fiber chicken egg
-   Once obtained, a fiber chicken egg can be placed in the vanilla incubator to hatch a fiber chicken
-   Added a Progression Mode to allow for unlocking of Level 2 and above chickens
-   Level 1 Chickens can only be individually disabled if Progression Mode is also disabled as all Level 1 Chickens are required for obtaining Level 2 Chickens
-   If Progression Mode is enabled, all Level 1 Chickens will be force enabled
-   Resource Chickens now have 2 appearance options in the configs (VanillaStyle, HattaStyle)
-   Added alternative custom sprites for all resource chickens (and baby chickens), done by [Tophatta](https://www.nexusmods.com/stardewvalley/users/54445652)!
-   Added an option to have vanilla chickens sprites also be changed to match Hatta Style resource chickens
-   Slightly changed Wood Egg sprite to match some custom egg sprites created by Tophatta
-   Changed egg item category to allow for use in cooking recipes
-   Changed egg edibility to match usability in cooking
-   Added second sprite for when Egg Resource Machine is processing
-   Removed redundant config options and repetitious lines in default.json to make translating easier for translators going forward

## 0.1.2

-   Added Chinese language support. Thanks [Orville9972](https://www.nexusmods.com/users/73926958)!

## 0.1.1

-   Quick change to disable swimming chickens by default (can be enabled in the config)

## 0.1.0

-   Initial release
-   Added Resource Chickens (Clay, Coal, Stone, Wood)
-   Added Resource Egg Converter Machine
