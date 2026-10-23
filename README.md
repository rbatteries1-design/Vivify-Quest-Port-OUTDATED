
THIS REPOSITORY IS OUTDATED AND IS MOST LIKELY NOT GONNA BE UPDATED, IF SOMEONE WISHES TO CONTINUE THIS PROJECT (collaborate)
PLEASE DM ME @5ymu <--- Discord

# Vivify Quest Port
------
## Instructions for building the project yourself
(You can build your own .qmod, just make sure to give credit if distributing)

## Requirements for build
* [Quest Package Manager](https://github.com/sc2ad/QuestPackageManager) (QPM)

### To build:
```
qpm restore
qpm s build
qpm s qmod
```

If you have QPM installed but throws an error, use `.\qpm` instead

## Installation

*For the best experience, mod your game using [ModsBeforeFriday](https://mbf.bsquest.xyz/) on version 1.40.8*

*A [tutorial](https://bsmg.wiki/quest/modding-with-mbf.html) by the Beat Saber Modding Group (BSMG)'s wiki for those who are new to this*
### Through ModsBeforeFriday (MBF)
1. Download the latest `vivify.qmod` file from the **Releases** tab, or build it yourself as shown above.
2. Once your headset is modded, connect it to your computer and drag and drop `vivify.qmod` into MBF.
3. Alternatively, click the **ADD FILES** button and select the `.qmod` file.
4. Safely disconnect your headset, then launch Beat Saber.

## .qmod Dependencies
**MOST OF THESE ARE CORE MODS INSTALLED WHEN YOU MOD USING MBF. INSTALL ANY MISSING MODS.**
* [beatsaber-hook](https://github.com/QuestPackageManager/beatsaber-hook)
* [custom-types](https://github.com/QuestPackageManager/Il2CppQuestTypePatching/)
* custom-json-data
* tracks
* [bsml](https://github.com/bsq-ports/Quest-BSML/)
* [songcore](https://github.com/raineaeternal/Quest-SongCore/)
* [paper2_scotland2](https://github.com/Fernthedev/paperlog/)
* web-utils
* [metacore](https://github.com/Fernthedev/paperlog/)

## Project dependencies (in qpm.json)

* beatsaber-hook ^6.4.2
* bs-cordl 4008.*
* custom-types ^0.18.4
* custom-json-data ^0.24.5
* tracks ^2.5.3
* songcore ^1.1.26
* bsml ^0.4.55
* config-utils ^2.0.3
* web-utils *
* scotland2 ^0.1.6
* paper2_scotland2 ^4.6.4
* conditional-dependencies ^0.3.0
* sombrero ^0.1.43
* cpp-semver ^0.1.2
* metacore ^1.0.3

## Credits
axo-lotl. (2026). GitHub - *axo-lotl/Vivify-Quest: vivify quest port (new repo for some reason).* GitHub. https://github.com/axo-lotl/vivify-quest

*This project contains code that was adapted from an open-source repository by [LookingForScripts1](https://github.com/Lookingforscripts1) that has since been deleted. Because the repository is no longer available, I am unfortunately unable to identify or link to the original repository.*

### Special thanks
Thank you to axo-lotl for giving version 0.4.0 early to meh :)

## License details
All rights reserved.

No part of this repository may be copied, modified, distributed, or incorporated into other software without the express written permission of the repository owner.
