overpochloot
============

Loot table for overPoch 1.0.5.1


###Add this to top of description.ext
```
#include "custom\loot\CfgBuildingLoot.hpp"
#include "custom\loot\cfgLoot.hpp"
#include "custom\loot\CfgLootSmall.hpp"
```

###Add this to init.sqf
```
DZE_MissionLootTable 		= true;
```

Add the loot folder to your mission folder of the **custom** folder is not there then create it.
```
Mission.pbo
|-- custom 
|----- Loot

```
