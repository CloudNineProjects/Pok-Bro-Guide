<style>
  body { background-color: #0d1117 !important; color: #e6edf3 !important; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif !important; }
  #header, header, .header, .btn, a.btn {
    display: none !important;
  }
  #main_content_wrap, .wrapper, section {
    margin-top: 0 !important;
    padding-top: 20px !important;
  }
  .markdown-body, .container-lg, .wrapper, section { background-color: #0d1117 !important; color: #e6edf3 !important; }
  a { color: #58a6ff !important; text-decoration: none; }
  a:hover { text-decoration: underline; }
  pre, code { background-color: #161b22 !important; color: #e6edf3 !important; border: 1px solid #30363d !important; border-radius: 6px; }
  blockquote { color: #8b949e !important; border-left: 4px solid #30363d !important; background-color: #161b22 !important; padding: 8px 16px; border-radius: 0 6px 6px 0; }
  table th, table td { border: 1px solid #30363d !important; padding: 6px 13px; }
  table th { background-color: #161b22 !important; }
  table tr { background-color: #0d1117 !important; }
  table tr:nth-child(2n) { background-color: #161b22 !important; }
  h1, h2 { border-bottom: 1px solid #21262d !important; padding-bottom: 0.3em; }
  hr { background-color: #30363d !important; height: 1px; border: 0; }

  /* Schwebendes Inhaltsverzeichnis oben rechts */
  .floating-toc {
    position: fixed;
    top: 16px;
    right: 16px;
    z-index: 9999;
    background-color: #161b22;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 8px 14px;
    box-shadow: 0 8px 24px rgba(0,0,0,0.6);
    max-width: 280px;
    font-size: 14px;
  }
  .floating-toc summary {
    cursor: pointer;
    font-weight: 600;
    color: #e6edf3;
    list-style: none;
    user-select: none;
  }
  .floating-toc summary::-webkit-details-marker { display: none; }
  .floating-toc ol {
    margin: 10px 0 4px 0;
    padding-left: 20px;
    max-height: 75vh;
    overflow-y: auto;
  }
  .floating-toc li { margin: 4px 0; }
</style>

<details class="floating-toc">
  <summary>📑 Table of Contents</summary>
  <ol>
    <li><a href="#core-concept">Core Concept</a></li>
    <li><a href="#controls--interface">Controls &amp; Interface</a></li>
    <li><a href="#cards-rarity--tiers">Cards, Rarity &amp; Tiers</a></li>
    <li><a href="#building-a-team">Building a Team</a></li>
    <li><a href="#how-battles-work">How Battles Work</a></li>
    <li><a href="#effects">Effects</a></li>
    <li><a href="#getting-pokémon">Getting Pokémon</a></li>
    <li><a href="#safari">Safari</a></li>
    <li><a href="#farm">Farm</a></li>
    <li><a href="#expedition">Expedition</a></li>
    <li><a href="#lab">Lab</a></li>
    <li><a href="#craft-business">Craft Business</a></li>
    <li><a href="#battle-tower--random-battles">Battle Tower &amp; Random Battles</a></li>
    <li><a href="#gym">Gym</a></li>
    <li><a href="#pokécenter--police-station">PokéCenter &amp; Police Station</a></li>
    <li><a href="#pokémart">PokéMart</a></li>
    <li><a href="#hub--players-house">Hub &amp; Player's House</a></li>
    <li><a href="#pokédex--missions">Pokédex &amp; Missions</a></li>
    <li><a href="#saving--accounts">Saving &amp; Accounts</a></li>
    <li><a href="#beginner-tips">Beginner Tips</a></li>
  </ol>
</details>

# PokéBro – Player Guide

Welcome to **PokéBro**! This guide covers the most important systems so you can get started quickly and know where to find what.

> Tip: Everything is saved in your browser. Use **☰ → Save** to export a backup or create an account for Cloud Save (see [Saving](#saving--accounts)).

---

## Table of Contents
1. [Core Concept](#core-concept)
2. [Controls & Interface](#controls--interface)
3. [Cards, Rarity & Tiers](#cards-rarity--tiers)
4. [Building a Team](#building-a-team)
5. [How Battles Work](#how-battles-work)
6. [Effects](#effects)
7. [Getting Pokémon](#getting-pokémon)
8. [Safari](#safari)
9. [Farm](#farm)
10. [Expedition](#expedition)
11. [Lab](#lab)
12. [Craft Business](#craft-business)
13. [Battle Tower & Random Battles](#battle-tower--random-battles)
14. [Gym](#gym)
15. [PokéCenter & Police Station](#pokécenter--police-station)
16. [PokéMart](#pokémart)
17. [Hub & Player's House](#hub--players-house)
18. [Pokédex & Missions](#pokédex--missions)
19. [Saving & Accounts](#saving--accounts)
20. [Beginner Tips](#beginner-tips)

---

## Core Concept

PokéBro is a collection and team-building game. You collect Pokémon as **cards**, build a team of three, and send it into automatic battles. Everything around the battles (Safari, Farm, Expedition, Lab, Crafting) feeds your collection and your resources.

The main loop:

1. Collect Pokémon (Safari, Region Summon, Eggs, Fossils, Expeditions …)
2. Build a strong team of **Attacker, Support, Defender**
3. Win battles and raids to earn PD (the in-game currency) and materials
4. Spend resources on crafting, upgrades and new Pokémon

---

## Controls & Interface

| Where | What |
|---|---|
| **Top bar** | Your PD (money). The ⌄ button opens the **Resources** popup (sorted by area). The 🎯 button opens the **Mission overview**. |
| **Hub** (home screen) | Your personal display. Decorate it with Pokémon, backgrounds and weather effects. The **World** button opens the town map. |
| **☰ Menu** | Teambuilder, Box, PokéDex, Guide, Save, Reset. Greyed out while a battle or minigame is running. |
| **World map** | Tap a building: Farm, Lab, Battle Tower, Gym, Craft Business, PokéMart, PokéCenter, Police Station, Docks (Safari & Region Summon), Player's House. |

**Moving in Safari and Expedition**

- **Keyboard:** WASD or arrow keys
- **Mouse:** hold the left button on the map and drag slightly in the direction you want to walk
- **Space:** interact (NPCs, baby Pokémon, doors …) or **Run** from an encounter
- **🔍 button:** switch between normal zoom and a full-map view

The game window scales automatically. Use the control bar at the bottom to change the size manually.

---

## Cards, Rarity & Tiers

Every Pokémon is a card with:

- **Total** (base stat total), **ATK**, **DEF**, **SPE**
- **Bonus values** (+0 to +94 per stat, rolled when you get the card)
- **Three effects**: **A** (Attack), **S** (Support), **D** (Defend)
- A rarity symbol, and optional badges: ✨ **Shiny**, **Alpha**, **Mythical**

**Shiny Pokémon always have the maximum bonus (+94) in all three stats.**

### Rarity (by Total)

| Rarity | Total |
|---|---|
| Common | up to 399 |
| Uncommon | 400–499 |
| Rare | 500–549 |
| Epic | 550+ |
| Legendary | flagged legendary Pokémon |

### Tiers (used for battles)

| Tier | Total |
|---|---|
| 1 – Beginner | 0–299 |
| 2 – Trainer | 300–399 |
| 3 – Challenger | 400–499 |
| 4 – Expert | 500–549 |
| 5 – Champion | 550+ |

Some battle modes require all three of your team members to be in the **same tier**.

### Box tools
In the **Box** you can filter by tier and region, sort (total stats, favorites, shinies) and search by Pokémon name or by effect name. **Favorites** (⭐) are protected from release. **Mass Release** removes all non-favorite, non-team Pokémon of one tier for PD.

---

## Building a Team

Open **☰ → Teambuilder**. You have **6 team slots** (renameable) with three positions each:

- **Attacker:** its **ATK** is your team's ATK and its **A-effect** (the attack) is used.
- **Support:** its **S-effect** is applied once at battle start.
- **Defender:** its **DEF** is your team's DEF and its **D-effect** is a passive ability.

**Team stats**

- **HP** = sum of the Totals of all three Pokémon
- **ATK** = the Attacker's higher attack stat + bonus
- **DEF** = the Defender's higher defense stat + bonus
- **SPE** = sum of the SPE (+ bonus) of all three

Extras you can add:

- **Mega / Mode Stones** (the **+** button under each slot): transform a compatible Pokémon with new stats. Crafted in the Construction Unit.
- **Cap** (the **+ Cap** slot): a crafted item that boosts team HP/ATK/DEF/SPE by percentages. The same cap applies to all team slots.

---

## How Battles Work

Battles run **automatically** and last **up to 30 turns**. If neither team is defeated by then, the enemy counts as the winner.

**Each turn:**

1. The team with the higher **current SPE** acts first.
2. Each team attacks with its Attacker effect.
3. End of turn: healing, poison/burn/sand damage, statuses tick down.

**Damage:** ATK × (move power ÷ 100), then reduced by the target's DEF. The defense reduction is roughly `(DEF ÷ 50 + 10) × 2` percent, **capped at 90%**.

**Other rules**

- **Stat stages** range from **−6 to +6** (ATK, DEF, SPE, ACC, EVA).
- **Critical hits** deal ×1.5 damage. Base crit chance is about 4%. Crit stages (CRT) raise it up to 100%.
- **Statuses** (Poison, Burn, Paralyze, Sleep, Freeze, Confusion, Flinch) last about 2 turns. Only one status at a time.
  - Burn halves ATK, Paralyze halves SPE (and can stop moves), Sleep and Freeze prevent attacking.
- **Weather** (Sun, Rain, Sand, Snow) and **Terrain** (Grassy, Electric, Psychic) are set by effects and change power or heal/damage each turn.
- Hover or tap an effect name to see its description.

---

## Effects

Effects are what make each card unique.

- **A – Attack effect:** a move with power, accuracy, tags and sometimes a secondary effect (status chance, drain, recoil, multi-hit, always-crit …).
- **S – Support effect:** a one-time boost at battle start (stat changes, weather, terrain, protection, debuffs for the enemy).
- **D – Defend effect:** a passive ability (power boosts for certain move tags, damage reduction, starting weather, survival effects …).

Effects come in five rarities: Common, Uncommon, Rare, Epic, Legendary. New cards roll their effects with these chances: 40% / 35% / 15% / 7.5% / 2.5%.

Good teams combine effects that work together, for example a weather-setting Support with an Attacker that benefits from that weather.

---

## Getting Pokémon

| Source | How it works |
|---|---|
| **Region Summon** (Docks → Region tab) | Opens 10 cards at once. Costs **25,000 PD** (50,000 PD with Shiny Charm mode, which also uses 1 Shiny Charm). Every 10th opening guarantees a shiny. A region unlocks when you beat its **Elite Four** in the Battle Tower. |
| **Safari** | Catch wild Pokémon in 12 biomes. |
| **Eggs** (Farm) | Variation Eggs and Regional Eggs (1,500 PD each at the Farmshop). |
| **Fossil Unit** (Lab) | Revive fossil Pokémon. |
| **Fusion Unit** (Lab) | Combine legendaries into fused forms (Kyurem, Calyrex, Necrozma). |
| **Reassembly Unit** (Lab) | Build Zygarde-10, -50 and -Complete from Cells and Cores. |
| **Expedition** | Evolution quests, Ancient Balls, Beast Balls, Paradox Balls, Legendary Cavern, Gholdengo trade. |
| **Lab Starters** | Free Alpha starter teams in three waves (needs 50 and 150 Pokédex entries for waves 2 and 3). |
| **Rescue Mission** (Police Station) | Win the end boss for a boosted Alpha Pokémon. |
| **Lure** (Farm) | Costs 1 Charm Stone + 25 of each berry. Gives a Pokémon you do not have yet. |
| **Unown Dex** (Expedition) | Collect all 28 Unown symbols for a guaranteed Shiny. |

---

## Safari

Enter Safari from the **Docks**. Pick one of **12 biomes**: Plains, Forest, Mountains, Cave, Snow, Swamp, Jungle, Desert, Volcanic, Beach, Graveyard, Ocean.

### Walking and encounters
Each step on a walkable tile has a **15% chance** of a wild encounter. Every step also counts toward your Farm production (see [Farm](#farm)).

### Catching
1. An encounter shows the Pokémon and its rarity.
2. Pick a ball. A ring minigame starts: **tap when the ball is inside the ring** (the ring turns green).
3. You have **3 attempts**. Higher rarity means a faster ball. Great and Ultra Balls slow the ball down.
4. **Master Ball** is a guaranteed catch.
5. **Run** (or Space) leaves the encounter.

| Ball | Shop price |
|---|---|
| PokéBall | 500 PD |
| Great Ball | 1,500 PD |
| Ultra Ball | 3,000 PD |

### Events and special encounters

- **Rarity Boost:** catching the same rarity repeatedly in one biome builds a streak that raises that rarity's spawn chance. At max streak you also get a Shiny multiplier. Catching a different rarity, a shiny, or letting one flee breaks it.
- **Swarm:** every day one biome has a Swarm Pokémon (shown on the map).
- **Mythical Roamer:** every day one biome hides a rare **Mythical** Pokémon. They are special cards that do not count for the Pokédex.
- **Alpha Encounter** (very rare): a powerful Pokémon. You can **Fight** it, **Calm** it (give berries, an Alpha item, or answer a question correctly: 2 successes lets you catch it) or **Run**. Alpha cards have max bonus stats.
- **Injured Pokémon** (very rare): help it with 1 Full Restore and receive a Lucky Egg.
- **Baby Pokémon:** appear occasionally. **Help** them to get a baby resource, which you can trade to Nurse Joy for TY Tokens.
- **Team E.V.I.L Ambush:** the bar in the info card fills with steps (300). When full, start the ambush battle for Badges, PD and balls. Losing costs some PD.

### Lures and items
- **Lure slot:** insert berries to limit encounters to Pokémon that match that berry. Berries are used up per encounter.
- **Items on the map:** Apricorns, berries, materials, nuggets, chests and more can be picked up by walking over them. Alpha items collected here (reset daily) are used in Calm attempts.

---

## Farm

The Farm produces resources **while you walk** in Safari or on Expeditions. All three modes count steps together.

| Building | Purpose |
|---|---|
| **Fields** | Grow Apricorns and Berries. **140 steps per item** per slot. |
| **Mine** | Produces Nuggets, Tumblestone and Iron Chunks. **140 steps per item**. |
| **Hatching** | Hatch eggs. An egg needs **1000 steps**. |
| **Farmshop** | Buy eggs and farm Pokémon, sell materials, trade Nuggets for berries. |
| **Farmhouse** | Change your farm skin. |
| **Fishing** | 3 attempts per day, rewards PD and Rainbow Scales. |
| **Bug Catching** | Memory-style minigame that rewards PD or Gold Bugs. |
| **Lure** | Spend a Charm Stone and berries for a guaranteed new Pokémon. |

**Storage:** each field and mine can hold **999** items. When it is full, production pauses. Open the building and collect.

**Farm Pokémon** (5,000 PD each in the Farmshop) boost production:

- Meganium / Rhydon / Chansey: reduce the steps needed
- Venusaur / Excadrill / Magmar: add extra slots

They level up to **Level 16** (500 PD per training), with a new boost every 2 levels.

**Hatching:** each egg is tied to a berry type and needs **10 of that berry** to hatch. There is a **30% chance the egg breaks** (a Cap perk can prevent this). The result is a regional or variation Pokémon, with a small shiny chance.

**Unlocking more slots:** start with 2 slots per building, up to 10.

---

## Expedition

Start from the **Lab → Expedition**. You need a full team.

### 1. The Entrance
Solve one trial (randomly chosen): an **Anagram**, a **Flute melody**, a **Regi alignment puzzle** or a **guardian boss battle**. You can also meet a **Diglett** (dig minigame) and a **quiz or puzzle NPC** for bonus rewards. Failing the entrance trial ends the expedition.

### 2. The Ruins
A series of connected rooms. Explore, open containers, collect items and Unown. Features:

- **Random fights** while walking on normal tiles (about 1.5% per step). Winning gives PD, evolution items, gems and materials. Losing costs HP.
- **HP:** you start with 100. Lava and acid tiles deal damage (10 per step). Heal with Heal Eggs. If HP hits 0, the run fails.
- **Evolution quests:** a Pokémon wants a specific evolution item. Hand it over for the evolved Pokémon.
- **Gem puzzle (Legendary Cavern):** use a Stoneplate and Gems to solve a type-chart puzzle and enter the Legendary Cavern.
- **Locked and blocked doors:** need an **Ancient Key** or a battle against a sleeping Snorlax/Slaking.
- **Teleport Abra:** costs a Teleport Stone, moves you across the room.
- **Portals:** Beast Portal and Time Rift lead to special maps with rare balls.
- **Team E.V.I.L Raiders:** tier-based fights with big rewards.
- **Boss:** a full **Raid Battle** (see [Lab](#lab)).

### 3. Finishing
- **End Expedition** at the exit tile: all collected resources are **secured and added** to your inventory.
- **Continue Deeper:** next floor, higher level, enemies are 20% stronger per level.
- **Quit or fail:** collected resources are **lost**. Buffs and some items are expedition-only.

> Resources in your expedition inventory are only safe after a successful exit.

---

## Lab

### Office
- **Missions (Prof. Mint):** pick one of three missions ("obtain X Pokémon"). Accepting generates three new ones. Completing five fills the **Bonus Gift** bar for a free random reward.
- **Expedition:** see above.
- **Starters:** claim free boosted Alpha starters (needs Pokédex entries for later waves).
- **Quiz:** a daily "Who's that Pokémon?" for **5,000 PD** plus balls.
- **PokéHex:** a hex-board strategy game against Assistant Plum, based on type matchups. Winner gets 5,000 PD, loser 1,000 PD.

### Research
- **Material Exchange:** sell materials for PD.
- **Construction Unit:** craft Shiny Charms, fusion items (Rein of Unity, DNA-Splicers, N-Solarizer, N-Lunarizer), Charm Stones, Stoneplates, all four ball types, and **Mega / Mode Stones**.
- **Fossil Unit:** Basic and Advanced Revive (also ×10).
- **Fusion Unit:** fuse two specific Pokémon plus a fusion item and 1000 Nuggets into a stronger form. The two Pokémon are **permanently consumed**.
- **Reassembly Unit:** craft Zygarde forms from Cells, Cores and Nuggets.

### Raid
Raids run as part of Expedition bosses. A raid consists of battles and card choices:

1. Match, 2. Boss debuff card, 3. Match, 4. Player buff card, 5. Match, 6. Item card, 7. **Boss battle**

Each won match removes one boss shield. Even if you do not defeat the boss, you earn rewards based on how much HP you took off. A win gives 10,000 PD, 100 Meteorite Shards and 50 Research Data, plus a chance at **Mega DNA** (needed for Mega Stones).

---

## Craft Business

- **Crafting**
  - *Materials:* Stuff, Metal, Reinforcement, Dye, Leather, Fastener
  - *Clothing:* **Trainer Caps** and **Trainer Buttons** (normal or Enhanced)
  - *Others:* Badge, Ancient Key, Teleport Stone
- **Material Exchange:** sell loot for PD.
- **Enhancement**
  - **Refinement:** reroll a Cap's stats using TY Vouchers (Basic = 1, Advanced = 5, with the option to keep the old result).
  - **Attachment:** socket Buttons into a Cap (slots depend on Cap rarity: 0 to 3).
  - **Dismantling:** break items down into materials.

**Caps** have 1–4 stat bonuses (HP/ATK/DEF/SPE in %). **Buttons** carry one perk such as better Safari shiny/alpha/rarity rates, more Expedition HP, damage reduction, Water Walk, Revive, or "eggs can't break". Perks only work from buttons socketed in your **equipped** Cap.

Rarities: Common, Rare, Epic, Legendary. Enhanced crafting gives better odds.

---

## Battle Tower & Random Battles

### Random Battle
Choose a tier. Your team's three Pokémon must match that tier (Champion is always available). Winning pays **100 PD**. After a loss you can rematch.

### Battle Tower
A run of up to **100 stages**.

- Reward per round: 50 / 100 / 150 / 200 / 250 PD depending on stage.
- **Stat cards** (+5% ATK, DEF or SPE) at stages 5, 15, 25 … 95.
- **Item cards** at stages 10, 20, 30 … 90. Items go into a hotbar (max 9). Click an item during a fight to activate it next turn. One item per fight.
- **Guest stages** at 20, 40, 60, 80, 100: you face an **Elite Four** of a random region (5 trainers in a row). Clearing it the first time **unlocks that region** for Region Summon.
- From stage 21, enemies get stronger every stage.
- **Losing ends the run.** PD you already earned is kept.

Your highscore and total wins are shown on the Tower screen.

---

## Gym

Located on the World map. It is abandoned at first. **Take it over for 100,000 PD.**

- **Recruitment:** buy trainers (Rookie, Trainer, Ace, Expert, Master) with PD. Daily reroll: the first is free, then the price doubles.
- **Roster:** train trainers to raise their Power (limited by their Potential, grade A to E). Roster size grows with Prestige.
- **Battle Area:** assign trainers to up to 8 slots plus the **Gym Leader** slot (slot 9, doubles that trainer's power). Some trainers have perks that buff neighbors, change types or boost the whole team.
- **Challenge:** costs **1 Badge** (craft in Craft Business). Waves of challengers walk through your slots. Each trainer deals damage with a type multiplier. Clear as many waves as possible for PD and **Prestige EXP**.
- **Daily attempts:** 1 per day, +1 at Prestige 10 and +1 at Prestige 20.
- **Prestige (up to 25):** unlocks roster slots, trainer slots, more waves, bonus PD and better recruit odds.

---

## PokéCenter & Police Station

**PokéCenter**
- **Potion Craft:** 20 Fresh Water + 10 King's Leaf = 1 **Full Restore**.
- **Baby Rescue:** hand over baby Pokémon from Safari to Nurse Joy for **5 TY Tokens** each.

**Police Station**
- **Rescue Mission** (once per day): a side-scrolling run with Magikarp. Jump over obstacles, collect items, avoid grass patches (they trigger a fight) and beat the end boss. Today's tier is shown on the button and your team must match it. You have 3 lives and 5 Action Points for extra jumps. Winning gives a boosted **Alpha Pokémon**.
- **Bounty:** exchange Team E.V.I.L Badges for TY Tokens (1:1).

---

## PokéMart

- **PokéBalls:** PokéBall 500 PD, Great Ball 1,500 PD, Ultra Ball 3,000 PD.
- **TY Voucher:** 100 TY Tokens each (used for Cap rerolls).
- **Cosmetic:** Hub backgrounds and Farm skins (50,000 PD), Player's House rooms (25,000 PD).
- **Gift Code:** redeem codes for PD and Shiny Charms. You must be **logged in**, and each code works once.

---

## Hub & Player's House

**Hub**
- Change your **background** and add **weather effects** (snow, rain, sunlight, fog, storm, blizzard, sandstorm and more).
- Place Pokémon from your Box (via the card menu in the Box). Drag them around, then tap to **lock**, **flip**, **scale** (scroll wheel) or change the **layer**.
- Save up to **6 hub layouts** with the save button and load them again.

**Player's House**
- Switch **Daylight / Moonlight** lighting, change the **room** and choose your **character** (male/female, also used in Safari and Expedition).
- **Decorate** with furniture from Expedition rare drops and Dex missions.

---

## Pokédex & Missions

The **PokéDex** tracks Normal and Shiny entries per region. Obtain info on each card shows where a Pokémon can be found.

**Dex Missions** (Dex → Missions tab) reward you for owning groups of Pokémon: PD, balls, Shiny Charms, Hub backgrounds and house decorations. Tap the ★ on a mission to **track** it in the mission overview (🎯 in the top bar).

---

## Saving & Accounts

Open **☰ → Save**:

- **Save:** saves in this browser. The game also saves automatically.
- **Export / Import:** download or load a backup file. **Do this regularly.**
- **Account and Cloud Save:** create an account with e-mail and password, then use **Cloud Save** and **Cloud Load** to move progress between devices.
- **Reset:** deletes everything. This cannot be undone.

If the game cannot load your save, it pauses saving so your old data is not overwritten. Reload the page or restore a backup.

---

## Beginner Tips

1. **Claim your Welcome Gift** the first time you open the World map (PD and balls).
2. Visit the **Lab → Starters** early for a free boosted team.
3. Build a full team and try **Random Battle** to learn the effect system.
4. **Walk in Safari** while your Farm works for you. Fill your Fields and Mine slots first.
5. Keep a stock of **balls**. Craft them in the Construction Unit when PD is short.
6. **Do the daily things:** Quiz, Fishing (3 tries), Rescue Mission, Gym challenge, Swarm and Mythical check.
7. Expeditions are risky: **exit successfully** to keep your loot. Heal Eggs and HP perks help.
8. Match the **tier** of your three Pokémon to unlock more battle modes.
9. Keep **favorites** (⭐) on cards you want to protect from release.
10. **Export your save** now and then.

Have fun, Trainer!
