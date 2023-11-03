Test repository for adding more men-at-arms regiments on Reamls in Exile with Dawnless Days(including submods) units.

This is for personal use, not meant to be balanced yet.

Simple guide for adding custom men-at-arms regiments
====================================================
### Crusader Wars mapper files
##### CW_LOTR_Factions.xml
```
  <FactionsGroups>
    <Faction name="Default">
      <MenAtArm type="**example maa title**" key="**Attila unit key in land_units_tables**" max="**regiment type**" script="**example_maa_unit_**"></MenAtArm>
    </Faction>
  </FactionsGroups>
```
1. type="**example maa title**"
2. key="**Attila unit key in land_units_tables**"
3. max="**regiment type**"
4. script="**example_maa_unit_**"



##### CW_LOTR_Cultures.xml
Cultures.xml modifying is not required to simply add custom regiments.

***
### Reamls in Exile files
##### lotr_elven_regiment_types.txt
File location: (/Realms in Exile/common/men_at_arms_types/)
