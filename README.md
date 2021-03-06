# PS4 Cheat Code / Offset List
![GitHub last commit](https://img.shields.io/github/last-commit/JDsnyke/PS4-Cheat-List.svg) ![GitHub issues](https://img.shields.io/github/issues/JDsnyke/PS4-Cheat-List.svg) ![GitHub pull requests](https://img.shields.io/github/issues-pr/JDsnyke/PS4-Cheat-List.svg) ![GitHub repo size in bytes](https://img.shields.io/github/repo-size/JDsnyke/PS4-Cheat-List.svg) ![license](https://img.shields.io/github/license/JDsnyke/PS4-Cheat-List.svg) [![Donate with Bitcoin](https://en.cryptobadges.io/badge/micro/1AQrV5YKDv3WnwEYddHr5UFtiTLUvQ5pQr)](https://en.cryptobadges.io/donate/1AQrV5YKDv3WnwEYddHr5UFtiTLUvQ5pQr)

List of PS4 cheat codes / offsets found for either [PS4Cheater](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/) or [NetCheatPS4](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/) :scroll:

## Table of Contents

* [Disclaimer](#disclaimer)

* [Information](#information)

* [Guides / Tutorials](#guides--tutorials)

* [How to use the Cheats](#how-to-use-the-cheats)

* [Contributions](#contributions)

* [Pull / Push Request Rules](#pull--push-request-rules)

* [List](#list)

## Disclaimer

All codes belong to their respective owners. I am merely gathering them here for ease of use.

I do not and cannot guarantee the accuracy nor the reliability of either these programs / software nor of these codes / offsets.

I nor the original publishers of these codes are to be blamed for any issues that arise with their use.

In other words, __USE AT YOUR OWN RISK__!

## Information

Original threads found [here](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/), [here](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/) and [here](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/) on the [psxhax](https://www.psxhax.com/) forum.

Also huge thread found [here](http://www.maxconsole.com/forums/ps4-game-cheat-codes.266/) at [maxconsole](http://www.maxconsole.com/) forum.

## Guides / Tutorials

* How to jailbreak your PS4 : [HERE](https://gbatemp.net/threads/aio-ps4-exploit-guide.497858/)

* How to dump PS4 game disc's into PKG files : [HERE](https://playstationhax.xyz/forums/topic/4260-how-to-rebuild-your-fake-signed-patched-raw-ps4-game-dump/)

* How to install Game updates (disc only) on a jailbroken PS4 : [HERE](https://www.youtube.com/watch?v=-6HzmOes8mw)

* How to find Game offsets / cheats for PS4 : [HERE](https://www.youtube.com/watch?v=GFOSc-bVbyg)

## How to use the Cheats

* Currently the easiest way to use cheats are to use the [cht](/cht/) files on [PS4Cheater 1.2](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/)

* The codes in the [list](#list) below are the corresponding addresses you should keep an eye out for on PS4Cheater and NetCheatPS4

* The NetCheatPS4 format : 0 FFFFFF (Address) FF (Value)

* The PS4Cheater format : listed similarly to NetCheatPS4 format in order to maintain uniformity

* Some offsets like this ````0xFFFFFF```` have been listed as ````0 FFFFFF```` in order to maintain uniformity

* The CHT File format (PS4Cheater 1.2):

    ````
    1.2|eboot.bin
    data|FF (?)|FFFFFF (Address)|4 bytes|FF (Value)|0 or 1|Name (eg: Money)|
    data|FF (?)|FFFFFF (Address)|4 bytes|FF (Value)|0 or 1|Name (eg: Potions)|
    ````

    ````
    1.2|eboot.bin
    data|25|7CD9A0|4 bytes|99|0|Apples|
    ````

* The end goal should be to use these codes / offsets to generate user friendly cht files!

## Contributions

I will update at my pace. What I have here is mostly incomplete and untested.

Feel free to [Fork](https://github.com/JDsnyke/PS4-Cheat-List/fork) and maintain your own versions. (Or even Push your Changes!)

## Pull / Push Request Rules

* Ensure you stay up to date with my repo and vice versa

* Please don't change the 'format' of the README.md unnecessarily (keep a uniform document across all forks)

* Maintain an alphabetical order

* Add relevant Title ID and Patch versions

* Add source next to game title

* If available, upload the relevant cht files and link it next to the game title

## List

> Tip - search using Ctrl + F on Windows or Command + F on Mac

> Tip - visit the included source links if you have any doubts

> Tip - cht files can be found [here](/cht/) or next to specific game titles

* Bloodborne (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-12#post-65721) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-13#post-65949
)

    ````
    Blood Echo [1]

    0 2082674C4
    0 208A674C4
    0 20840C06C
    ````

    ````
    Blood Echo [2]

    0 207C0C08C
    0 2082674E4
    0 21369B7D8
    0 225B03FF8
    0 311F17738
    0 311F17740
    0 311F197F0
    ````

* Bloodborne Game of the Year Edition (CUSA03173 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73944) [[CHT File]](/cht/Bloodborne_GOTY_(CUSA03173-Ver_1.0.0).cht)

    ````
    Blood Echo

    0 C674C4
    ````

* Call of Duty : Black Ops 3 (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/)

    ````
    Player State

    0 21A8164

    Index

    0 17010

    Freeze (0x01 - frozen) (0x00 - unfrozen)

    0 21A8167

    Flag (0x04 - default) (0x05 - godmode) (0x06 - spectate) (0x07 - spectate w/ godmode)

    0 21A8180

    Location X, Y, Z

    0 21A8190

    Killstreak 1, 2 and 3

    0 21A87AC
    0 21A87B0
    0 21A87B4

    Primary Ammo Reserve

    0 21A87B8

    Secondary Ammo Reserve

    0 21A87BC

    Ammo 1, 2, 3, 4, 5 and 6

    0 21A87F4
    0 21A87F8
    0 21A87FC
    0 21A8800
    0 21A8804
    0 21A8808

    UAV (0x00 - default) (0x02 - scramble uav)

    0 21A88E4

    Vision (0x00 - default) (0x80 - thermal)

    0 21A88E9

    Body State (0x00 - default) (0x01 - cloak) (0x02 - hologram)

    0 21A88F9

    Name

    0 21BED64

    Zombies Primary Ammo Reserve

    0 21A87AC

    Zombies Secondary Ammo Reserve

    0 21A87B4

    Zombies Ammo

    0 21A87E8

    Zombies Points

    0 21BEE14
    ````

* Call of Duty : Ghosts (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/)

    ````
    FPS (80, 78, 10, 01)

    0 81B09A

    FPS String

    0 BDEDE5

    Name

    0 1F0F29C

    Primary Weapon

    0 1F0C26C

    Primary Ammo - Clip

    0 1F0C454

    Primary Ammo - Stock

    0 1F0C3D4

    Secondary Ammo - Clip

    0 1F0C460

    Secondary Ammo - Akimbo Clip

    0 1F0C464

    Grenade Ammo

    0 1F0C43C

    Tactical Ammo

    0 1F0C448
    ````

* Call of Duty : Infinite Warfare (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/)

    ````
    Player State

    0 3D3E540

    Index

    0 6CC8

    Location X, Y, Z

    0 3D3E560

    Name

    0 3D430FC

    Radar (0x00 - scramble uav) (0x02 - default)

    0 3D431B4

    Primary Reserve Ammo

    0 3D3EDEC

    Secondary Reserve Ammo

    0 3D3EE04

    Ammo 1, 2 and 3

    0 3D3EF54
    0 3D3EF78
    0 3D3F008

    Zombies Reserve Ammo 1 and 2

    0 3D3EE04
    0 3D3EE4C

    Zombies Ammo 1 and 2

    0 3D3EF78
    0 3D3EFC0
    ````

* Call of Duty : Modern Warfare Remastered (CUSAXXXXX - Ver 1.0.7 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-62317)

    ````
    Name

    0 7347322

    Scoreboard Score, Kills, Deaths and Assists - 0x2 Bytes (FF FF = 65535)

    0 73473CE
    0 73473D0
    0 73473D2
    0 73473D4

    Ammo - 0x3 Bytes (FF FF FF = Infinite)

    Primary Ammo Clip

    0 7342E28

    Primary Ammo Reserve

    0 7342D5C

    Secondary Ammo Clip

    0 7342DF8

    Secondary Ammo Reserve

    0 7342D44

    Grenade Ammo

    0 7342E10

    Tactical Ammo

    0 7342E40

    Grenade Launcher Attachment (uses Tactical Ammo)

    0 7342E58

    Perk Ammo

    0 7342E58
    ````

* Crash Bandicoot N Sane Trilogy (CUSAXXXXX - Ver X.X.X - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-18#post-71778) [[CHT File]](/cht/Crash_Bandicoot_N_Sane_Trilogy_(CUSAXXXXX-Ver_X.X.X).cht)

    ````
    Apples

    0 7CD9A0
    ````

* Dark Souls 3 - Game of the Year (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-2#post-73360) [[CHT File]](/cht/Dark_Souls_3_(CUSAXXXXX-Ver_X.X.X).cht)

    ````
    Souls

    1 9A9B34
    1 3E17670
    1 3E1A8EC
    1 3E1A8F0
    1 6CCA1A8
    1 6CCA1AC
    ````

* Dead Island : Definitive Edition (CUSAXXXXX - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](https://playstationhax.xyz/forums/topic/4414-dead-island-definitive-edition-ps4-cheater-455-cheat-codes/)

    ````
    Cash

    0 401F882DF8
    ````

* Dead Rising 1 HD Remake (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/dead-rising-1-hd-remake-cheat-codes.46552/)

    ````
    PP

    21E28928C
    ````

* Diablo 3 (CUSA00433 - Ver X.X.X - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-64673)

    ````
    Gold (address changes on restart)

    0 20C71D3CC
    ````

* Dragon Quest Heroes (CUSA02769 - Ver X.X.X - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-6#post-74099) [[CHT File]](/cht/Dragon_Quest_Heroes_(CUSA02769-Ver_X.X.X).cht)

    ````
    Money

    0 1FFB40

    Minimedals

    0 1FFB44

    Aila Max EXP

    0 1F45C8

    Aurora Max EXP

    0 1F4424

    Luceus Max EXP

    0 1F44B0

    Alena Max EXP

    0 1F4654

    Doric Max EXP

    0 1F4654

    Kiryl Max EXP

    0 1F46E0
    ````

* FIFA 15 (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-9#post-63548)

    ````
    Money

    0 50030671D0 3B9AC9FF
    ````

* Final Fantasy XV (CUSAXXXXX - Ver X.X.X - Firm X.XX - PS4Cheater 1.2 [1] and NetCheatPS4 [2]) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-17#post-71001) [[2]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-10#post-63601) [[CHT File]](/cht/Final_Fantasy_XV_(CUSAXXXXX-Ver_X.X.X).cht)

    ````
    Infinite Health [2]

    0 50030671DC

    Money [2]

    0 50030671D0

    All Characters Max Exp [2]

    0 5002EC06C0
    0 5002ECB7C0
    0 5002ED68C0
    0 5002EE19C0

    Items (In Location Order - 1, 2, 3 ... 10) [1]

    0 310620C
    0 3106214
    0 310621C
    0 3106224
    0 310622C
    0 3106234
    0 310623C
    0 3106244
    0 310624C
    0 3106254

    Ingredients (In Location Order - 1, 2, 3 ... 10) [1]

    0 3106C0C
    0 3106C14
    0 3106C1C
    0 3106C24
    0 3106C2C
    0 3106C34
    0 3106C3C
    0 3106C44
    0 3106C4C
    0 3106C65

    Treasures (In Location Order - 1, 2, 3 ... 10) [1]

    0 3107414
    0 310741C
    0 3107424
    0 310742C
    0 3107434
    0 310743C
    0 3107444
    0 310744C
    0 3107454
    0 310745C

    Auto Parts (In Location Order - 1, 2, 3 ... 10) [1]

    0 3107C0C
    0 3107C14
    0 3107C1C
    0 3107C24
    0 3107C2C
    0 3107C34
    0 3107C3C
    0 3107C44
    0 3107C4C
    0 3107C54

    Leisure Goods (In Location Order - 1, 2, 3 ... 10) [1]

    0 310840C
    0 3108414
    0 310841C
    0 3108424
    0 310842C
    0 3108434
    0 310843C
    0 3108444
    0 310844C
    0 3108454

    Key Items (In Location Order - 1, 2, 3 ... 10) [1]

    0 310640C
    0 3106414
    0 310641C
    0 3106424
    0 310642C
    0 3106434
    0 310643C
    0 3106444
    0 310644C
    0 3106454
    ````

* God Eater 2 : Rage Burst (CUSA03370 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-72994) [[CHT File]](/cht/God_Eater_2_Rage_Burst_(CUSA03370-Ver_X.X.X).cht)

    ````
    Money

    0 19EB90
    ````

* Gravity Rush (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-12#post-64486)

    ````
    Gems

    0 264522937
    ````

* Gravity Rush 2 (CUSA03694 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-2#post-58385)

    ````
    Gems

    0 01E7A2AC
    0 01E7A2B0
    ````

* Horizon Zero Dawn (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-9#post-65171) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-11#post-65434)

    ````
    Arrows [1]

    0 F5CF09E84

    Metal Pieces [1]

    0 24CEDAF84
    0 25CF2D9B4

    Skills [2]

    0 200E9E81F
    0 200EA0ECB
    0 25CF8212C
    0 25D915190
    0 264C68899
    ````

* Kingdom Hearts 2.8 (CUSA05787 - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/kingdom-hearts-2-8-cheat-codes.46553/)

    ````
    Sora Munny

    0 2F65C44C

    Sora EXP

    0 2F6A3DA0

    Meow Wow EXP

    0 2F654524
    ````

* Kingdom Hearts 2.8 (CUSAXXXXX - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](https://playstationhax.xyz/forums/topic/4415-kingdom-hearts-28-ps4-cheater-455-cheat-codes/)

    ````
    Sora Munny

    0 D5844C

    Ability Links

    0 D5052C

    Main Character EXP

    0 D9FDA0
    0 D583CC
    ````

* Mortal Kombat X Standard Edition (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-12#post-65610)

    ````
    No Money Krypt

    0 037688A4
    0 037688A8
    0 037688D0
    ````

* NieR Automata (CUSA04551 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73436) [[CHT File]](/cht/NieR_Automata_(CUSA04551-Ver_1.0.0).cht)

    ````
    Money

    0 4A1810

    EXP (Set Exp 9999999 -> To get Max LvL 99)

    0 4A99C0

    Medium Recovery (Minimum 1 MR required first)

    1 4A1828
    ````

* Persona 5 (CUSA06638 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73753) [[CHT File]](/cht/Persona_5_(CUSA06638-Ver_1.0.0).cht)

    ````
    Money

    0 36674

    Medicine (Max 99)

    0 35BB0

    Main Character EXP (Set your exp, after 1 Battle you get the lvl ups)

    0 3373C

    Main Character HP (Max 999)

    1 3372C

    Main Character Skill Points (Max 999)

    1 33730
    ````

* Resident Evil Origins : RE 0 (CUSA02461 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](https://playstationhax.xyz/forums/topic/4413-re-origins-collection-re-0-ps4-cheater-455-codes/)

    ````
    Handgun Ammo and Equipped Ammo (Slot 01)

    0 20D0EFCDC

    Ink Ribbon (Slot 04)

    0 20D14D554
    ````

* Tales of Zestiria (CUSA02461 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/ps4-cheater.4529/page-2#post-64700)

    ````
    Sorey Exp

    0 103DE7D5BC

    Edna Exp

    0 103DE8E2FC

    Rose Exp

    0 103DE8193C

    Zaveid Exp

    0 103DE9697C

    Lailah Exp

    0 103DE89FBC

    Mikleo Exp

    0 103DE85C7C

    Money

    0 103F605F60

    All Consumables

    0 103DE01024
    0 103DE01028
    0 103DE0102C
    0 103DE01030
    0 103DE01034
    0 103DE01038
    0 103DE0103C
    0 103DE01040
    0 103DE01044
    0 103DE01048
    0 103DE0104C
    0 103DE01050
    0 103DE01054
    0 103DE01058
    0 103DE0105C
    0 103DE01060
    0 103DE01064
    0 103DE01068
    0 103DE0106C
    0 103DE01070
    0 103DE01074
    0 103DE01078
    0 103DE0107C
    0 103DE01080
    0 103DE01084
    0 103DE01088
    ````

* Uncharted Trilogy (CUSA02343 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-2#post-58321)

    ````
    Uncharted 1 - 1st Weapon Bullets

    0 00EA5444

    Uncharted 1 - 2nd Weapon Bullets

    0 00EA54F8
    ````

* Yakuza 0 (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-6#post-64825)

    ````
    Money (Dynamic Address - always 2nd value in memory map of size 372,800 KB)

    0 209E8F2B0
    ````

* Yakuza 6 (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-9#post-63548)

    ````
    Money

    0 2023B1D38
    ````

* Yakuza Ishin (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4)  [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-11#post-63905)

    ````
    Money

    0 2003E6BC8 3B9AC9FF
    ````

## License

Uses the [MIT](https://github.com/JDsnyke/PS4-Cheat-List/blob/master/LICENSE) license.
