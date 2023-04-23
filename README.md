# DayZ-ServerConfig

Config files for the DayZ Server

"[PVE] Surviving the Green Hell together |Zones|NoRaid|Expension"

IP: 51.195.8.21
Test Server: 51.195.96.217

WIP ...

!!!! Trading Zones: Don't override STOCK!!!!!


ToDo:
- change trader outfit/NPC at GreenMountain
- LANDROVER LESS SPAWN
- launcher ammo seperate categorie (no buy at normapl trader!)



MOD ID's:

@1559212036;@1564026768;@2545327648;@2572331007;@2116157322;@2793893086;@2792983824;@2831742849;@1932611410;@2536888090;@2443122116;@2663169692;@2950964578;@2800339728;@1832448183;@2860643107;@2921256386;@2827018523;@2345073965


<!-- .......................................... -->  
<!-- add to econemycore.xml & cfgrandompreset.xml -->
<!-- .......................................... -->  

<ce folder="db_split">
    <!-- Vanilla Types Split -->
        <file name="VT_Ammo.xml" type="types" />
        <file name="VT_Animals.xml" type="types" />
        <file name="VT_Attachments.xml" type="types" />
        <file name="VT_Base.xml" type="types" />
        <file name="VT_Civ_Clothing.xml" type="types" />
        <file name="VT_Components.xml" type="types" />
        <file name="VT_Containers.xml" type="types" />
        <file name="VT_Drinks.xml" type="types" />
        <file name="VT_Explosives.xml" type="types" />
        <file name="VT_Food.xml" type="types" />
        <file name="VT_Life_Only.xml" type="types" />
        <file name="VT_Medical.xml" type="types" />
        <file name="VT_Melee.xml" type="types" />
        <file name="VT_Mil_Clothing.xml" type="types" />
        <file name="VT_Seasonal.xml" type="types" />
        <file name="VT_Tools.xml" type="types" />
        <file name="VT_Vehicles.xml" type="types" />
        <file name="VT_Weapons.xml" type="types" />
        <file name="VT_Zombies.xml" type="types" />
    </ce>

<ce folder="expansion_ce">
		<file name="expansion_types.xml" type="types" />
		<file name="expansion_spawnabletypes.xml" type="spawnabletypes" />
		<file name="expansion_events.xml" type="events" />
	</ce>

<ce folder="db_custom">
	<!-- Mod Types -->
		<file name="BL_BoomLayThings_types.xml" type="types" />
		<file name="CJ_LootChest-CJ187_types.xml" type="types" />
		<file name="CJ_LootChest-CJ187_cfgspawnabletypes.xml" type="spawnabletypes" />
		<file name="CP_CannabisPlus_types.xml" type="types" />
		<file name="MMG_cfgspawnabletypes.xml" type="spawnabletypes" />
		<file name="MMG_Storage.xml" type="types" />
		<file name="MMG_types_ADMINGEAR.xml" type="types" />
		<file name="MMG_types_alpine.xml" type="types" />
		<file name="MMG_types_atacs.xml" type="types" />
		<file name="MMG_types_black.xml" type="types" />
		<file name="MMG_types_carbines.xml" type="types" />
		<file name="MMG_types_dark_woodland.xml" type="types" />
		<file name="MMG_types_erdl.xml" type="types" />
		<file name="MMG_types_green.xml" type="types" />
		<file name="MMG_types_multicam.xml" type="types" />
		<file name="MMG_types_multicam_tropic.xml" type="types" />
		<file name="MMG_types_multicamblack.xml" type="types" />
		<file name="MMG_types_NBC+NVG.xml" type="types" />
		<file name="MMG_types_patches.xml" type="types" />
		<file name="MMG_types_police.xml" type="types" />
		<file name="MMG_types_tan.xml" type="types" />
		<file name="MMG_types_ucp.xml" type="types" />
		<file name="MMGCC_CivilianClothing_types.xml" type="types" />
		<file name="RUSForma_Types.xml" type="types" />
		<file name="SLC_Swords_types.xml" type="types" />
		<file name="SLC_Swords_spawnabletypes.xml" type="spawnabletypes" />
		<file name="SNAFU_types.xml" type="types" />
		<file name="SNAFU_spawnabletypes.xml" type="spawnabletypes" />
	</ce>
	
	cfg_randompresets
	
<cargo chance="0.15" name="toolsHermit">
				<item name="WeaponCleaningKit" chance="0.10" />
				<item name="Matchbox" chance="0.15" />
				<item name="CanOpener" chance="0.05" />
				<item name="Rope" chance="0.07" />
				<item name="Rag" chance="0.07" />
				<item name="CJ_Key1" chance="0.01" />
				<item name="CJ_Key2" chance="0.01" />
				<item name="Hatchet" chance="0.07" />
				<item name="StoneKnife" chance="0.1" />
				<item name="HuntingKnife" chance="0.08" />
				<item name="PurificationTablets" chance="0.05" />
				<item name="CharcoalTablets" chance="0.05" />
		</cargo>
		<cargo chance="0.25" name="toolsPolice">
				<item name="Battery9V" chance="0.1" />
				<item name="PersonalRadio" chance="0.1" />
				<item name="Flashlight" chance="0.15" />
				<item name="Roadflare" chance="0.2" />
				<item name="CombatKnife" chance="0.05" />
				<item name="Morphine" chance="0.05" />
				<item name="CJ_Key1" chance="0.01" />
				<item name="CJ_Key2" chance="0.01" />
				<item name="BandageDressing" chance="0.05" />
		</cargo>
		<cargo chance="0.35" name="toolsIndustrial">
				<item name="Pipe" chance="0.07" />
				<item name="Hatchet" chance="0.07" />
				<item name="Crowbar" chance="0.07" />
				<item name="Rope" chance="0.1" />
				<item name="DuctTape" chance="0.1" />
				<item name="CJ_Key2" chance="0.01" />
				<item name="Battery9V" chance="0.2" />
				<item name="Flashlight" chance="0.2" />
		</cargo>
		<cargo chance="0.1" name="mixArmy">
				<item name="SodaCan_Cola" chance="0.05" />
				<item name="SodaCan_Pipsi" chance="0.05" />
				<item name="SodaCan_Spite" chance="0.05" />
				<item name="TunaCan" chance="0.1" />
				<item name="SardinesCan" chance="0.05" />
				<item name="CJ_Key3" chance="0.01" />
				<item name="PeachesCan" chance="0.05" />
				<item name="SpaghettiCan" chance="0.05" />
				<item name="BakedBeansCan" chance="0.05" />
				<item name="TacticalBaconCan" chance="0.1" />
				<item name="Canteen" chance="0.1" />
				<item name="Ammo_45ACP" chance="0.2" />
				<item name="AmmoBox_45ACP_25Rnd" chance="0.05" />
				<item name="Ammo_762x39" chance="0.2" />
				<item name="AmmoBox_762x39_20Rnd" chance="0.05" />
				<item name="Ammo_762x54" chance="0.2" />
				<item name="AmmoBox_762x54_20Rnd" chance="0.05" />
		</cargo>




