Trash Does Not Consume Bait
=================================

**THIS IS AN ARCHIVE: PLEASE SEE [https://github.com/atravita-mods/StardewMods](https://github.com/atravita-mods/StardewMods) for the updated repo.**

This mod prevents trash from consuming bait. Additionally, it adds automatic replacement of tackles/bait when they run out. When replacing, the code will try to use the same bait/tackle you were using, but if you don't have that particular tackle/bait remaining in your inventory, it can optionally use whatever you have on hand. It will only use bait/tackle in your inventory.

## Install

1. Install the latest version of [SMAPI](https://smapi.io).
2. Download this mod and unzip it into `Stardew Valley/Mods`.
3. Run the game using SMAPI.

## Configuration

1. `AutomaticRefill`: Toggles the automatic refill feature.
2. `SameTackleOnly`: Replacement tackles have to be the same type as the one used up.
3. `SameBaitOnly`: Replacement bait have to be the same type as the one used up.
4. `ConsumeChanceNormal`: The probability that a fishing rod without the Preserving enchantment consumes bait/tackle. (Default: 1 = 100%)
5. `ConsumeChancePreserving`: The probability that a fishing rod with the Preserving enchantment consumes bait/tackle. (Default: 0.5 = 50%)
6. `CrabPotTrashDoesNotEatBait`: Whether crab pot trash should eat bait.

## Compatibility

* Works with Stardew Valley 1.5.6 on Linux/macOS/Windows.
* Works in single player, multiplayer, and split-screen mode. Should be fine if installed for one player only.
* Should be compatible with most other mods. (If you use [Everlasting Bait and Unbreakable Tackles](https://www.nexusmods.com/stardewvalley/mods/2360), you may see the stack size of your bait increase or your tackle repair though. [Unbreakable Tackles](https://www.nexusmods.com/stardewvalley/mods/7719) is closed source - or at least I couldn't find the source - so I don't know how this mod interacts with that one. You could alternately just set the consume chance to be zero though.)

Technical note: this mod transpiles `FishingRod.doDoneFishing`, so it's not likely to be compatiable with any mod that also transpiles that function.

## See also

[Changelog](TrashDoesNotConsumeBait/docs/Changelog.md)
