Test repository for adding more men-at-arms regiments on Reamls in Exile with Dawnless Days(including submods) units.

This is for personal use, not meant to be balanced yet.

Simple guide for adding custom men-at-arms regiments
====================================================
# Crusader Wars mapper files
### CW_LOTR_Factions.xml
Example: 
```
  <FactionsGroups>
    <Faction name="Default">
      <MenAtArm type="Border Guards" key="exe_wr_border_guards" max="INFANTRY" script="border_guards_unit_"></MenAtArm>
    </Faction>
  </FactionsGroups>
```
1. type="**example maa title**"
2. key="**Attila unit key in land_units_tables**"
3. max="**regiment type**" (variables: INFANTRY, CAVALRY, RANGED, numbers for monsterous units)
4. script="**example_maa_unit_**"

### CW_LOTR_Cultures.xml
Cultures.xml modifying is not required to simply add custom regiments.

***
# Reamls in Exile files
### lotr_elven_regiment_types.txt
File location: (/Realms in Exile/common/men_at_arms_types/)
