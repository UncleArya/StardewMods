# Changelog

## 1.6.0

-	Added compatibility with [More Lively Farm Cave](https://www.nexusmods.com/stardewvalley/mods/23190)
-	if Additional Farm Cave is installed, the correct map edit should automatically apply

## 1.5.1

-	Updated display name from 'Farm' to 'Farm Cave' for improved compatibility with [Integrated Minecarts](https://www.nexusmods.com/stardewvalley/mods/11881)
-	Added compatibility for when both [Additional Farm Cave](https://www.nexusmods.com/stardewvalley/mods/14109) and [Hot Spring Farm Cave](https://www.nexusmods.com/stardewvalley/mods/5849) are present
-	Updated map patch for Additional Farm Cave and Hot Springs Farm Cave

## 1.5.0

-	Added compatibility with [Additional Farm Cave](https://www.nexusmods.com/stardewvalley/mods/14109)
-	Additional Farm Cave: Minecart is in the additional cave area unlocked after the Demetrius farm cave event
-	Additional Farm Cave: Return spawn is at the back of the entrance cave, due to how that mod patches the vanilla Farm Cave
-	Updated Content Patcher format version

## 1.4.0

-	added compatibility with [Hot Spring Farm Cave](https://www.nexusmods.com/stardewvalley/mods/5849)
-	if Hot Spring Farm Cave is installed, the correct map edit should automatically apply
-	changed internal location string ID from *FarmCave* to *unclearya.farmcaveminecart.FarmCave* to align with CP best practices and avoid potential conflicts in naming with other mods

## 1.3.0

-   changed map patching method to reduce file size and potentially improve some compatibility
-   code cleanup

## 1.2.0

-   added a config toggle for "Compatibility Mode" which greatly simplifies the map edits to attempt improving- some compatibility with other custom Farm Cave maps

## 1.1.3

-   minor tweaks to potentially improve some compatibility for custom Farm Cave maps (likely still mostly- incompatible with custom Farm Cave maps)

## 1.1.2

-   added a config option in GMCM to allow for entering a custom value for the minecart location name
-   defaults to 'Farm' (or the translated word for Farm if a translation is included)

## 1.1.1

-   added translations for German, Spanish, Portuguese, French, and Chinese

## 1.1.0

-   updated for SDV 1.6
-   removed dependency for MinecartPatcher as it is no longer needed in 1.6
-   slight design change to remove dependency for DaisyNiko's Tilesheets

## 1.0

-   initial release
