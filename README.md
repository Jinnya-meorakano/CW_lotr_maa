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
1. type="**Regiment title**"
2. key="**Attila unit key in land_units_tables**"
3. max="**regiment type**" (variables: INFANTRY, CAVALRY, RANGED, numbers for monsterous units)
4. script="**regiment_title_unit_**"



### CW_LOTR_Cultures.xml
Cultures.xml modifying is not required to simply add custom regiments.

***
# Reamls in Exile files
### lotr_elven_regiment_types.txt
File location: (/Realms in Exile/common/men_at_arms_types/)


For detailed information: https://ck3.paradoxwikis.com/Regiments_modding


Example:
```
### Noldor ###
## - The armies of the Noldor are few in number in the dwindling days of the Third Age, but in quality are unparalleled
# Noldor Swordsman (Heavy Infantry)
noldor_swordsmen = {
	can_recruit = { noldor_trigger = yes }
	type = heavy_infantry

  ================
  CUSTOM MAA STATS
  ================

	ai_quality = { value = culture_ai_weight_heavy_infantry }
	icon = heavy_infantry
	allowed_in_hired_troops = no
}
```
1. Faction: ### Faction name ###


2. Regiment info:
 * Regiment title (Type)
 * regiment_title
 * can_recruit = { **faction**_trigger = yes }
 * type = (pikemen, heavy_infantry, archers, heavy_cavalry, skirmishers, siege_weapon)

### lotr_maa_l_english.yml
File location: (/Realms in Exile/localization/english/culture/)
