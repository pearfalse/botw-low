# low%

A candidate route for a Breath of the Wild low% speedrun. Includes IST scripts and Celer2 route.

# Ruleset

Progress counts as:

## Inventory

- Number of unlocked tabs
- Maximum number of occupied slots
- Highest quantity of stackable items\*

## World

- Picked-up static equipment and materials\*
- Killed enemies\*
- Visited locations
- Completed shrine and korok counters\*

## Flags

- Number of quests obtained, progressed, completed
- Number of inventory slot upgrades purchased\*
- Number of memories recovered\*

\* = immaterial in current route; we can avoid these entirely

## Proposed exceptions

- Map progress percentage: Some map locations (Hyrule Castle, Sanctum) are technically avoidable in the _post-Ganon save_, but doing this takes more effort for little benefit. We don't even have the Slate to check in the final completed file, so low map % feels like a separate challenge.
- DLC armor and _Xenoblade Chronicles 2_ side quests: unavoidable when reloading off plat with DLC installed. Current route requires DLC, and asking players to uninstall DLC _mid-run_ is unconscionable.

# This Route

This route plays through the game three times:

- The first playthrough starts a new run from a fresh boot of the game, as per standard rules. It completes plat, and obtains items and quest progress for further glitches.
- The second playthrough is under Extended Memory Storage and 3 offset, to transfer the four minimally required items into a SoR autosave. We then apply a wrong warp to that save, so that Link is directly outside the Sanctum.
- The third playthrough is what actually completes the game, with all typical plat progress bypassed.

# FAQ (Fully Anticipated Question)

<dl>
<dt>oh god why did you put <em>memory storage</em> in this what is your <em>problem</em></dt>
<dd>The NG+ file that actually beats the game has the following inventory requirements:

- No pre-transfer inventory
- Must include working paraglider
- Must not collect additional items, locations, or quest progress

Unfortunately this very particular combination is not possible with IST, as we'd have no way within the SoR to get back to positive `mCount` and stop transferring the same glider.
</dd>
