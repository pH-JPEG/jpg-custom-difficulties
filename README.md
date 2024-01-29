# jpg-custom-difficulties
json files of difficulties that I have created for the Deep Rock Galactic mod [Custom Difficulty](https://mod.io/g/drg/m/custom-difficulty).

## [Main Difficulties](https://github.com/pH-JPEG/jpg-custom-difficulties/tree/main/Main%20Difficulties)
These are the "high-effort" difficulties I've created, intended to be another way to enjoy a (mostly) 6x2-esque experience in modded DRG. The list is chronological with more recently released difficulties at the bottom.

**Suggested Difficulties:**
The suggested difficulties to play are [6x2EX](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2EX/6x2EX.json), [ND](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/ND/ND.json), and [Send It!](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Send%20It!.json). 6x2EX is a good introduction of the style of difficulties I make while being an approachable step-up from standard 6x2. ND is the next step-up if you want a significant increase in difficulty from 6x2. Send It offers an alternative gameplay loop compared to more traditional difficulties.

All the Main difficulties I've created are:
- [6x2 Breeder Edition (6x2B)](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2B.json)
  - 6x2, but Breeders can respawn. They also spawn Shockers.
  - *Latest update:* MinPoolSize 13->15. 
- [6x2 w/ Sentinels and Fire Bombers](https://github.com/pH-JPEG/jpg-custom-difficulties/tree/main/Main%20Difficulties/6x2SEFB) (6x2SEFB, with [rc1](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2SEFB/6x2SEFB_rc1.json), [rc4](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2SEFB/6x2SEFB_rc4.json), and [SK](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2SEFB/6x2SEFB-SK.json) denoting version)
  - 6x2, but Sentinels and Fire Bombers can spawn in missions.
  - [rc1](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2SEFB/6x2SEFB_rc1.json): The original release version.
  - [rc4](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2SEFB/6x2SEFB_rc4.json): The current recommended version that reduces amount of Sentinels and increases Fire Bomber amounts.
  - [SK](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2SEFB/6x2SEFB-SK.json): Based on version rc4. Stalkers can now spawn in missions.
  - *Latest update:* rc1, rc4: MinPoolSize 13->16. SK: MinPoolSize 16->17.
- [Lunatic (Lx2)](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2/Lx2.json)
  - Where the cave madness began. Made to experiment and push limits with difficulty created for difficulty's sake, balance be damned. Features are listed [here](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2/Lx2%20Features.txt).
  - *Latest update:* Stingtails take x1 damage.
  - **Disclaimer:** From an objective game design perspective, Lx2 is incredibly unbalanced. It is extremely punishing of any mistakes and highly RNG-based, with certain mission and biome combinations becoming near impossible from the start due to cave generation, encounter/stationary spawns, and nitra spawns. Build diversity no longer exists with degenerate strategies showing up more frequently. Don't expect to win even with highly experienced players. Overall, it is a major departure from 6x2 and should not be used as a metric for balancing difficulties or weapon balance discussions. That said, this difficulty is made for those who find extreme variance and occasional outright BS enjoyable while pushing their patience and the vanilla game weapons to the limit.
  - [Lx2 Simple Bug Enhance](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2/Lx2%20Simple%20Bug%20Enhance.json): Lx2 intended for use with the mod [Simple Bug Enhance](https://mod.io/g/drg/m/simple-bug-enhance). You start with a resupply. Don't use this version without Simple Bug Enhance.
  - [Lx2 Carry (Lx2C)](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2/Lx2C.json): Lx2 always scaled to 4 players independent of current player amount.
- [Send It!](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Send%20It!.json)
  - Takes 6x2, removes timed swarms, and causes waves of bugs to spawn frequently. Encounter and Stationary spawns are reduced. Play on only Mining, Egg, Salvage, and Refinery missions, unless you have mods that allow Send It to be compatible/more enjoyable with Elimination, Escort, Point Extraction and Sabotage. 
  - *Latest update:* MinPoolSize 13->14.
- [6x2EX](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2EX/6x2EX.json)
  - **REQUIRES THE MORE ENEMY VARIANTS MOD BY YINNY.** This mod can be found in the [Practical DRG Discord](https://discord.gg/hFkqMXPBzA) under the modding-forum channel as its own post labeled "WIP More Enemy Variants (MEV)." Without the mod, a host cannot load the difficulty file in Custom Difficulty while some enemies are invisible to a client who joined a 6x2EX lobby without downloading MEV.
  - A 6x2-based, more fair version of Lx2. More consistent and less disruptive enemy spam. Features are listed [here](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2EX/6x2EX%20Features.txt).
  - *Latest update:* Grunt Rarity 3->1.5. Grunts from Nexuses, Swarmer Tunnels, and Swarmer Eggs are now white.
  - [6x2EX Simple Bug Enhance](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2EX/6x2EX%20Simple%20Bug%20Enhance.json): 6x2EX intended for use with the mod [Simple Bug Enhance](https://mod.io/g/drg/m/simple-bug-enhance). Don't use this version without Simple Bug Enhance.
- [Lunatic-Extra (Lx2EX)](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2EX/Lx2EX.json)
  - Lx2, but with even more ridiculous features and RNG. Features and differences from Lx2 [here](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2EX/Lx2EX%20Features.txt).
  - *Latest update:* Stingtails take x1 damage.
  - **Disclaimer:** As this is just Lx2 but even harder, this is more unbalanced. You have been warned.
  - [Lx2EX Simple Bug Enhance](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2EX/Lx2EX%20Simple%20Bug%20Enhance.json): Lx2EX intended for use with the mod [Simple Bug Enhance](https://mod.io/g/drg/m/simple-bug-enhance). Don't use this version without Simple Bug Enhance.
  - [Lx2EX Carry (Lx2EX-C)](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/Lx2EX/Lx2EX-C.json): Lx2EX always scaled to 4 players independent of current player amount.
- [6x2LX](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2LX/6x2LX.json)
  - **REQUIRES THE MORE ENEMY VARIANTS MOD BY YINNY.** This mod can be found in the [Practical DRG Discord](https://discord.gg/hFkqMXPBzA) under the modding-forum channel as its own post labeled "WIP More Enemy Variants (MEV)." Without the mod, a host cannot load the difficulty file in Custom Difficulty while some enemies are invisible to a client who joined a 6x2LX lobby without downloading MEV.
  - 6x2EX, but with 4 features from Lx2EX. Additions are listed [here](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2LX/6x2LX%20Features.txt).
  - *Latest update:* Grunt Rarity 3->1.5. Grunts from Nexuses, Swarmer Tunnels, and Swarmer Eggs are now white.
  - [6x2LX Simple Bug Enhance](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/6x2LX/6x2LX%20Simple%20Bug%20Enhance.json): 6x2LX intended for use with the mod [Simple Bug Enhance](https://mod.io/g/drg/m/simple-bug-enhance). Don't use this version without Simple Bug Enhance.
- [ND](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/ND/ND.json)
  - **REQUIRES THE MORE ENEMY VARIANTS MOD BY YINNY.** This mod can be found in the [Practical DRG Discord](https://discord.gg/hFkqMXPBzA) under the modding-forum channel as its own post labeled "WIP More Enemy Variants (MEV)." Without the mod, a host cannot load the difficulty file in Custom Difficulty while some enemies are invisible to a client who joined a ND lobby without downloading MEV.
  - The more balanced, consistent, and polished successor to Lx2 and Lx2EX which serves as an initial experiment with MEV. Features are listed [here](https://github.com/pH-JPEG/jpg-custom-difficulties/blob/main/Main%20Difficulties/ND/ND%20Features.txt).
  - *Latest update:* Renamed difficulty to ND.

## [WIP Difficulties](https://github.com/pH-JPEG/jpg-custom-difficulties/tree/main/WIP%20Difficulties)
Difficulties that are currently being tested. All versions will be uploaded to the corresponding difficulty's folder. Upon completion, all pre-release versions will be moved to the Alpha/Beta Versions folder.

## [Meme Difficulties](https://github.com/pH-JPEG/jpg-custom-difficulties/tree/main/Meme%20Difficulties)
Self-explanatory, these are intentionally dumb ideas meant as jokes. Highly unbalanced and likely unplayable.

## [Alpha/Beta Versions](https://github.com/pH-JPEG/jpg-custom-difficulties/tree/main/Alpha%20and%20Beta%20Versions)
Older versions of some of the main difficulties.
