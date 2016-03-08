# HomeworldRemastered_Mothership
Campaign mothership modification for Homeworld Classic: Remastered

Homeworld Campaign; Singleplayer; Mothership modification

all files are written in lua, simple modifications made to mothership weapon types, health, regeneration, and fun tweaks to the junkyarddog

files are pulled directly from .big files in Homeworld\HomeworldRM\DataUpdates  and installed to Homeworld\HomeworldRM\Data

any ships, weapon types, or weapons not directly used by the game engine in the .big files in "DataUpdates" folder are stored in .big files in the main "Homeworld\HomeworldRM\Data" folder. The game engine looks for and overwrites files in this order: \DataUpdates, then \Data, and lastly individual directories/folders within the \Data folders. eg. weapons, missiles, ships, etc

Must use launch options to force .big file overrides.
Use these launcher options:
-dlccampaign HW1Campaign.big -campaign HomeworldClassic -moviepath DataHW1Campaign -overrideBigFile -luatrace

version 1.00:

-changed station weapon type

-weapon types are "flak" and "missile"; instead of six generic "HDefense" turrets
  
  -4 flak types with increased damage and range
  
  -2 missile types with increased damage, range, flight time, increased AOE, and increased multiple target detection radius
  

-increased station health, regeneration, and engagement ranges to 15km
  
  -creates and "area of denial" effect for later campaign missions where the game engine generates rediculous amounts of units;                "matching" the difficulty of your available units
