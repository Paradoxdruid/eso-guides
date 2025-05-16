# Paradoxdruid's ESO Guides

*This is a work in progess; last updated 2025-05-16*

These represent Paradoxdruid's best attempt at capturing the mid-tier meta for U46 (groups who regularly do vet and some vet HM content; not trifecta progs or scorepushing attempts). 

**Wait, you've got it all wrong!**  Yeah, maybe I do, that's totally fair.  And in any case, there's lots of goos approaches and strategies, and not a one-size-fits-all approach that will always apply.  I added a brief discussion of [Other Approaches](#other-approaches) towards the end of the document, to point out a few other common thoughts, and why I'm not currently recommending them.  

Thanks for all the feedback I've received to date!

---------------------------------------

# ESO Update 46 Mid-tier Build Guides

See [Guiding Principles](#guiding-principles) and [Buff Calculations](#buff-calculations) for explanations of set selections.

## Example Support Loadouts

| Role | Class Lines | Skill Bar Links | Typical Sets | Notes |
| ---- | ----------- | --------------- | ------------ | ----- |
| **Main Tank** | Winter's Embrace (Warden), Soldier of Apocrypha (Arcanist), Earthern Heart (Dragonknight) | [MT skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=28,139,26,211,33,419,206,270,430,288,136,408) | Pearl/Yolna/Tremor, Crimson/Yolna/Naz | Can use Runic Sunder instead of Inner Rage for increased penetration<br>Typical Ult: Aggressive Horn |
| **Off Tank** | Daedric Summoning (Sorcerer), Bone Tyrant (Necromancer), Siphoning (Nightblade) |  [OT skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=152,359,403,218,223,419,221,270,430,415,69,145) | Sax/PA/AD, Sax/Pearl/AD, Sax/Lucent/AD |  Typical Ult: Charged Atronach |
| **MA/JO Healer** | Siphoning (Nightblade), Restoring Light (Templar), Gravelord (Necromancer) |  [MAPA skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=319,412,406,323,64,419,385,270,104,102,398,228) | MA/JO/Spaulder or Ozezan, MA/PA/Spaulder or Ozezan | Typical Ult: Glacial Colossus |
| **SPC/MA (or PP) Healer** | Green Balance (Warden), Siphoning (Nightblade), Curative Runeforms (Arcanist) | [SPC skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=319,431,320,323,64,60,196,270,406,412,3,419) | SPC (FB staff, ring, 2 body)/MA (or PP) (5 body)/Pearls/Potentates (ring + BB staff) | Role is to reduce ult cost and spam Barrier on cooldown<br>Typical Ult: Barrier |

<!-- Table inside collapsed section broken in leapDay theme?
<details>

<summary>Support loadout skills details</summary>

* **MT**: *FB:* Impervious Runeward, Igneous Shield, Runic Sunder, Polar Wind, Runegaurd of Still Waters, Replenishing Barrier; *BB:* Expansive Frost Cloak, Elemental Blockade, Leashing Soul, Elemental Susceptibility, Igneous Weapons, Aggressive Horn
* **OT**: *FB:* Hardened Ward, Exhilarating Drain, Inner Rage, Hungry Scythe, Necrotic Potency, Replenishing Barrier; *BB:* Summoning Armor, Elemental Blockade, Leashing Soul, Elemental Susceptibility, Siphoning Attacks, Charged Atronach
* **MAPA Healer**:  *FB:* Illustrious Healing, Echoing Vigor, Energy Orb, Combat Prayer, Healthy Offering, Replenishing Barrier; *BB:* Warding Contingency, Elemental Blockade, Extended Ritual, Radiant Aura, Overflowing Altar, Aggressive Horn
* **SPC Healer**:  *FB:* Illustrious Healing, Healing Burst, Radiating Regeneration, Combat Prayer, Healthy Offering, Replenishing Barrier; *BB:* Budding Seeds, Elemental Blockade, Energy Orb, Echoing Vigor, Trample, Glacial Colossus
 
</details>
-->

## Example DPS Loadouts

| Type | Class Lines | Skill Bar Links | Typical Sets | Notes |
| ---- | ----------- | --------------- | ------------ | ----- |
| **Meta Beam Arcanist** | Herald of the Tome (Arcanist), Assassination (Nightblade), Aedric Spear (Templar) | [Beam skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=299,370,18,16,429,36,20,274,22,47,429,12) | Null Arca/Deadly Strikes/Velothi/Maelstrom Inferno (or Maelstrom Greatsword) | Aedric Spear is for passives only, can easily swap to Gravelord, Ardent Flame, Dawn's Wrath or others<br>For increased Crit damage, slot [Spear FB](https://sheumais.github.io/esoskillbarbuilder/?skills=299,81,18,16,429,36,20,274,22,47,429,12) |
| **Blastbones Necro** | Gravelord (Necromancer), Assassination (Nightblade), Aedric Spear (Templar) | [Necro skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=231,234,232,238,429,36,237,334,336,47,429,228) | Corpseburster/Null Arca/Velthi/Maelstrom Greatsword | Aedric Spear is for passives only, can easily swap to Ardent Flame, Dawn's Wrath, Animal Companions, or others |
| **Non-Beam Nightblade** | Assassination (Nightblade), Herald of the Tome (Arcanist), Stormcalling (Sorcerer) | [NB skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=43,39,46,19,429,36,173,20,334,372,429,12) | Null Arca/Tideborn/Velothi/Maelstrom Greatsword | Lots of flexibility with Stormcalling line for others |
| **Zen DK** |  Ardent Flame (Dragonknight), Dawn's Wrath (Templar), Assassination (Nightblade) | [DK skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=43,372,113,111,114,36,47,119,334,380,87,109) | Z'en's Redress/Null Arca/Velothi/Maelstrom Greatsword or Inferno Staff | Lots of line flexibility |
| **Frost Focused** | Winter's Embrace (Warden), Herald of the Tome (Arcanist), Assassination (Nightblade) | [Frost skill bars](https://sheumais.github.io/esoskillbarbuilder/?skills=372,47,14,19,429,36,21,334,210,209,429,36) | Null Arca or Whorl of the Depths/Ice Furnace or Frostbite/Velothi/Maelstrom Ice Staff |  |

----------------------------------------------

# ESO Update 46 Mid-tier Trial Rosters

These rosters should be ready to copy and paste into Discord, though you may need to check the custom icons based on your servers and emoji availability.

## vet Maw of Lorkhaj

```md
Your Local Time:

**Reqs**: Please state role(s) when signing up. Dps must parse 90K. Will take 3 without clear.

**Addons**: Crutch Alerts, Ody's Support Icons, Hodors (for supports)

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
MT [Pearl/Yoln/Tremor]: *[Frost Cloak :TANK_warden:; Igneous Weapons  :TankDK: ]*
OT [Sax/PA/AD]:  *[Charged Atronach :TANKsorc: ]* 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
H [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*
H [MA/JO/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
M1: [Z'en]
M2: [MK]
M3:
M4:
R1:
R2:
R3:
R4:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Runners
L:
M:
R:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Fill
```

## vet Halls of Fabrication
```md
Your Local Time:

**Reqs**: Please state role(s) when signing up. Dps must parse 90K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: Crutch Alerts, Ody's Support Icons

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
**RIGHT STACK (Reactor)**
MT [Yoln/Crimson/Naz] (Purge for first boss): *[Frost Cloak :TANK_warden:; Igneous Weapons :TankDK: ]*
H [MA/PA/Spaulder or Ozezan] (Purge):  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]*
DPS: [Z'en]
DPS:
DPS:
DPS:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
**LEFT STACK (Reducer)**
OT [Sax/Pearl/Nunatak] (Purge for First Boss): *[Charged Atronach :TANKsorc:  ]*
H [SPC/MA/Pearls/Potentates] (Purge):  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*
DPS: 
DPS:
DPS:
DPS: 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Portals
N:
E:
S:
W:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Fill
```

## vet Asylum Sanctorium

```md
Your Local Time:

**Reqs**

*(All Beam users slot Reaving Blows :large_blue_diamond: )*
*(All banners: Magic/Heroism)*

**Addons**: Asylum Sanctorium Status Panel, Asylum Tracker, Elms Markers

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
MT [Crimson/Yoln/Naz]  *[Frost Cloak :TANK_warden:; Igneous Weapons :TankDK: ]*
OT [Sax/Pearl/Spaulder] *[Charged Atronach :TANKsorc:  ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
GH [SPC/MA] *[Budding Seeds :HEAL_warden:; Healthy Offering :HEAL_NB:; Barrier ]*
FK [Zen/MA/AD]  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Healthy Offering :HEAL_NB: ; Glacial Colossus :HEAL_necro: ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
L1:  *[ Pragmatic Fatecarver :Arc_STAM: ]*
L2: *[ Pragmatic Fatecarver :Arc_STAM: ]*
L3: *[ Pragmatic Fatecarver :Arc_STAM: ]*
L4: *[ Pragmatic Fatecarver :Arc_STAM: ]*
L5 [RO/JO/Oakensoul]  (interrupts) *[Glacial Colossus :STAM_necro:  ]*
L6:  *[ Pragmatic Fatecarver :Arc_STAM: ]* 
L7:  *[ Pragmatic Fatecarver :Arc_STAM: ]*
L8:   *[ Pragmatic Fatecarver :Arc_STAM: ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
```

## vet Cloudrest

```md
Your Local Time: 

**Reqs**: Please state role(s) when signing up. Dps must parse 90K. Will take 3 without clear.

*(NO OAKENSOUL)*
*(All banners: Magic/Heroism)*

**Addons**: HowTo Cloudrest, Ody's Support Icons, Lock Weapon Swap
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Mini Tank [Crimson/Yoln/Spauld]: *[Frost Cloak :TANK_warden:; Charged Atronach :TANKsorc:  ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Portal Tank 1 [Sax/Pearl/AD]: Steed mundus - Ele Sus Z'Maja/Crystal: *[Igneous Weapons :TankDK: ]*
Portal Tank 2 [Sax/Pearl/Naz]: Steed Mundus - Ele Sus Z'Maja/Crystals:  *[Igneous Weapons :TankDK: ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Healers
R Group Healer: [MA/PA/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]*
L Kite Healer: [SPC/MA/Pearls/Potentates] (Ele Sus Grapes):  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
PORTAL 1
L DPS CW: 
L DPS CCW: 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
PORTAL 2
L DPS CW:
L DPS CCW: 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
R BACKUP PORTAL 1 DPS [Z’en]: 
R BACKUP PORTAL 2 DPS: 
R GRAPE SLAYER:
```

## vet Sunspire
```md
Your Local Time:

**Reqs**: Please state role(s) when signing up. Dps must parse 95K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: HowTo Sunspire, Crutch Alerts, Ody's Support Icons, Hodors

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
MT [Pearl/Yoln/Tremor]:  *[Frost Cloak :TANK_warden:; Igneous Weapons  :TankDK:  ]*
OT [Sax/PA/AD]:  *[Charged Atronach :TANKsorc: ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
**HEAD STACK**
Tomb H [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*
1: [Z'en]
2: 
3: 
4:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
**WING STACK**
GH [MA/JO/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]*
5: 
6:
7:
8:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
PORTAL:
L:
M: 
R:
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
TOMBS:
T1:
T2:
T3:
Backup:
```

## vet Kyne's Aegis
```md
Your Local Time: 

**Reqs**: Please state role(s) when signing up. Dps must parse 95K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: HowTo Kynes, Crutch Alerts, Ody's Support Icons, Hodors
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
MT [Pearl/Yoln/Tremor]: *[Frost Cloak :TANK_warden:; Igneous Weapons  :TankDK: ]*
OT [Sax/PA/AD] (Guard): *[Charged Atronach :TANKsorc: ]* 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
H [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*
H [MA/JO/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]* 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
M1 [Z'en]:  
M2 [MK]:   
M3:  
M4:  
R1:  
R2:    
R3: 
R4: 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

Fill:
```

## vet Rockgrove
```md
Your Local Time: 

**Reqs**: Please state role(s) when signing up. Dps must parse 105K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: Qcells Rockgrove Helper, Crutch Alerts, Ody's Support Icons, Hodors

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
MT: [Crimson/Yoln/Naz]: *[Frost Cloak :TANK_warden:;  Igneous Weapons :TankDK: ]*
OT: [Pearl/Sax/Spaulder] (Lord Warden on Bahsei): *[Summoning Armor :TANK_necro: ; Charged Atronach :TANK_sorc: ]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
KH: [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*
GH: [MA/PA/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]* 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
DPS: [Zen] 
DPS: (Guard): 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
1.1:
1.2: 
1.3: 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
2.1:
2.2:
2.3:
```

## vet Dreadsail Reef
```md
Your Local Time:

**Reqs**: Please state role(s) when signing up. Dps must parse 95K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: Qcell's Dreadsail Reef Helper, Crutch Alerts, Ody's Support Icons

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
**RIGHT STACK**
MT [Yoln/Crimson/Naz]: *[Frost Cloak :TANK_warden:; Igneous Weapons  :TankDK: ]*
H [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:;  Barrier ]*
M1 top right: 
M2 bottom right: 
M3 dome swap:  
M4 [Z'en]: 

**LEFT STACK**
OT [Pearl/Sax/AD]:  *[Charged Atronach :TANKsorc:  ]* 
H [MA/PA/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]* 
M1 top left:
M2 bottom left: 
M3 dome swap: 
M4: 

**BOSS 2 RUNNERS**
1: 
2: 
3: 
Backup 1: 
Backup 2: 

**BOSS 3 BRIDGES**
1: 
2: 
3:
```

## vet Sanity's Edge

```md
Your Local Time:

**Reqs**: Please state role(s) when signing up. Dps must parse 95K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: Crutch Alerts, Ody's Support Icons, Hodor's

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
MT [Yoln/Crimson/Naz]: *[Frost Cloak :TANK_warden: ; Igneous Weapons  :TankDK: ]*
OT [Pearl/Sax/AD]: *[Charged Atronach :TANKsorc: ]* 

H1 [MA/PA/Spaulder or Ozezan]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]* 
H2 [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*

1 [Z'en]:
2: 
3 (portal):
4 (portal):
5 (portal):
6: 
7:
8: 
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
```

## vet Lucent Citadel
```md
Your Local Time:

**Reqs**: Please state role(s) when signing up. Dps must parse 95K. Will take 3 without clear.

*(All banners: Magic/Heroism)*

**Addons**: Crutch Alerts, Ody's Support Icons, Hodor's

▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
**GARGOYLE**
MT [Yoln/Crimson/Naz]: *[Frost Cloak :TANK_warden: ; Igneous Weapons  :TankDK: ]*
(W 90 /S 60) H1: [SPC/MA/Pearls/Potentates]:  *[Budding Seeds :HEAL_warden: ; Healthy Offering :HEAL_NB:; Barrier ]*

S DPS: 
SW DPS: 
W DPS:  *[Glacial Colossus :stam_necro: first boss]*
NW DPS: 

**SCORPION**
OT [Pearl/Sax/AD]:  *[ Charged Atronach :TANKsorc:  ]* (kite boss 2)
(E 90 / N 60) H2: [MA/PA/Spaulder or Ozezan, SPC/MA first boss]:  *[Radiant Aura :HEAL_templar:; Extended Ritual :HEAL_templar: ; Glacial Colossus :HEAL_necro: ; Healthy Offering :HEAL_NB: ]*   
N DPS: 
NE DPS: 
E DPS:  
SE DPS: [Zen] *[Igneous Weapons :STAM_DK:  boss 1]*
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
Knot:
1
2
3
4
5
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
```

-------------------------------------------------

# Notes

## Guiding Principles

* Most dps will be in meta Arc/NB combos, which feature high penetration and crit damage.  With Reaving Blows CP and/or Pragmatic Fatecarver, they have high innate survivability.
* Mid-tier players aren't perfect yet at stacking when needed, so effective use of slayer stacks is difficult.
* Due to meta classes being Arc/NB, there is no need for Roar of Alkosh, Elemental Catalyst, or Crimson Oath's Rive sets in most fights (see calculations below).
* With the changes to Zena's (targets 6, not smart targeting), sourcing Minor Courage requires a change.  Both healers in Healing Burst with Courage affix is possible, but again doesn't smart target.  All Banners in Courage works, but requires expensive Heroism potions.  Tank in Yolnakriin is the easiest source to reliably get everyone Minor Courage.  The recovery buffs from Zena's are moved to a healer running Radiant Aura.
* With changes to ult gen, pillager's profit is no longer worth it, but it's possible for healers to generate enough ult to spam low cost Barrier and Colossus ults almost on cooldown.

## Buff Calculations

* **Typical Meta Penetration (Arc/NB):**
  * Major Breach (Ele Sus) 5,948
  * Minor Breach (Cruxweaver on MT or good Brittle uptimes) 2,974
  * Crusher 2,108
  * Piercing Blue CP 700
  * (just a note, NB Master Assassin grants crit and not penetration now)
  * (Null Arca and Deadliy Strikes have no Pen lines)
  * Velothi: 1,650
  * Arcanist passives, 2 abilities slotted (Flail and Beam): 2,480
  * (optional: 1 Light Armor 939)
  * SUBTOTAL: 15,860; need 2,340 to reach cap
  * Tremorscale 2,640 (or Runic Sunder 2,200)
  * **TOTAL**: 18,500 (18,060 with sunder)
  * Overcap with no need for Kosh or Crimson

* **Typical Meta Crit Damage (Arc/NB):**
  * Base 50%
  * Minor Brittle 10%
  * Velothi / Minor Force 10%
  * 7 Medium armor 14% (optional: 6 pieces works, too)
  * Nightblade passive 10%
  * Arcanist passive 12%
  * Major Force (Horn and Sax) 20% 
  * **TOTAL**: 126%
  * (optional Lucent Echoes 11%, if bad Major Force uptimes)
  * Overcap with no need for EC

## Other Approaches

* One likely approach is putting DPS players in Courage Banner; this means the Tank doesn't need to run Yolna.  **Why I don't recommend:**
  *  In U46, there's less "must-have" tank sets, given the high crit damage and penetration.
  *  Minor Heroism is difficult to source--  the best options are Banner or Heroism pots, and most mid-tier groups can't afford to pop Heroism pots on cooldown and/or are bad at constantly chugging potions in general.
* What happened to ROJO?  **Why I don't recommend:**
  * First off, ROJO is still a great setup, and there's nothing wrong with it, per se.
  * But with the increased Ult generation available to healers, "spammable" ult sets and ults become more useful, allowing high uptimes just from ult generation.
  * ROJO's major weakness--  requiring HAs that slow down casting.  These lower ult gen from ult-generating spammables and reduce raw casts available.
* High-tier groups often run Berserk on the Banner.  They source other buffs; Savagery from potions and heroism from Torchbearer, for example.  **Why I don't recommend:**
  * For mid-tier groups, "fire and forget" buffs, such as always-on Camo Hunter lead to substantially higher uptimes and don't require as much player skill and coordination to achieve good results.
* Healers getting big Pillager ults has been the meta for a while.  **Why I don't recommend:**
  * With the increased Ult generation available to healers in U46, "spammable" ult sets and ults become more useful, allowing high uptimes just from ult generation.
  * Additionally, Pillagers was nerfed to 40% of it's former effectiveness, and the Pearls nerf reduces the ability to get those maximized pillager's ults.
  * However, it's still a unique buff, and I'm sure it will still see use.
* Why worry about Major Force?  Run Lucent Echoes and/or EC, have DPS players slot a spear ability, and you don't need Major Force at all.  **Why I don't recommend**:
  * With the increased Ult generation available to Off Tanks in U46, "spammable" ult sets and ults become more useful, allowing high uptimes just from ult generation.  An OT in Sax can have very high Major Force uptimes, especially if MT runs Horn as well.
  * Aggressive Horn remains a unique stat buff and is worthwhile even if major force is less required.
  * Focusing on buffs with previously low uptimes, like Major Berserk from Atronach, will lead to higher group DPS.
  * For mid-tier groups, we expect a range of preparedness and sets from players.  Reducing the need for EC, Lucent Echoes, etc makes the roster more accessible for less well geared-out players.


## Changelog

* 2025-05-16: Added Other approaches section, fully gave up on Pillager's in suggested setups.
* 2025-05-15: Fixed Tank mentions of required Runic Sunder.  Added note that Beam arcs can slot spear for increased crit damage.
* 2025-05-14: Adjusted Healer roles and sets to reflect the ability to spam Barrier and maximize Major Slayer uptimes.  Swapped Tank sets for Sax and no TT.
* 2025-05-13: Added Buff calculations to explain why certain sets aren't needed; added explanation of Yolnakriin meta.  Changed skill layouts to table form to include notes.
* 2025-05-12: Moved Glacial Colossus to SPC Healer; kept Reaving Blows CP requirement only for vAS; revised MT and OT lines to move Winter's Embrace to MT and add Siphoning to OT
* 2025-05-11: Initial setups
