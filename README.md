# DayZ-ServerConfig

Config files for the DayZ Server
"[PVE] Surviving the Green Hell together |Zones|NoRaid|Expension"

IP: 51.195.8.21
Test Server: 51.195.96.217


ToDo:
- P2P trader: test Vehicle spawn position
- Book: HM MAchine infos
- Ai Loadout: more randomised loot
- Add Aircraft carrier back in
- Test Wind Simulation
- Add Expansion Gate Kit??
- More airdrop types (with guards?)
- CJ Loot Chest: more randomised Loot
- Add Boltensteins Race Track DZE
- Heli spawn in the Woodsd (Ai Camp)


Ideas:
- Hunting quests: specific types (as a quest row; bring back pelts?)
- Radio emergency frequency

Bugs
- ARFARF Base despawn
- Virtual Garage: blocked by world items (e.g. heli pad)
- Closed Barrels in RUS Vehicles (Garage storage)

New Mods:
- Kamensk mine DZW install
- SNAFU Damage Mod (wait for Mod update)
- Fortifications mod



Info
Tutoria




MOD ID's:

@1559212036;@1564026768;@2545327648;@2572331007;@2116157322;@2793893086;@2792983824;@2831742849;@1932611410;@2536888090;@2443122116;@2663169692;@2950964578;@2800339728;@1832448183;@2860643107;@2921256386;@2827018523;@2345073965;@2976244400;@2977778411;@1646187754;@2982956046;@2651195301



<!-- .......................................... -->  
<!-- add to cfg_randompresets.xml  -->
<!-- .......................................... -->  	
<cargo chance="0.15" name="toolsHermit">
				< name="WeaponCleaningKit" chance="0.10" />
				< name="Matchbox" chance="0.15" />
				< name="CanOpener" chance="0.05" />
				< name="Rope" chance="0.07" />
				< name="Rag" chance="0.07" />
				< name="CJ_Key1" chance="0.01" />
				< name="CJ_Key2" chance="0.01" />
				< name="Hatchet" chance="0.07" />
				< name="StoneKnife" chance="0.1" />
				< name="HuntingKnife" chance="0.08" />
				< name="PurificationTablets" chance="0.05" />
				< name="CharcoalTablets" chance="0.05" />
		</cargo>
		<cargo chance="0.25" name="toolsPolice">
				< name="Battery9V" chance="0.1" />
				< name="PersonalRadio" chance="0.1" />
				< name="Flashlight" chance="0.15" />
				< name="Roadflare" chance="0.2" />
				< name="CombatKnife" chance="0.05" />
				< name="Morphine" chance="0.05" />
				< name="CJ_Key1" chance="0.01" />
				< name="CJ_Key2" chance="0.01" />
				< name="BandageDressing" chance="0.05" />
		</cargo>
		<cargo chance="0.35" name="toolsIndustrial">
				< name="Pipe" chance="0.07" />
				< name="Hatchet" chance="0.07" />
				< name="Crowbar" chance="0.07" />
				< name="Rope" chance="0.1" />
				< name="DuctTape" chance="0.1" />
				< name="CJ_Key2" chance="0.01" />
				< name="Battery9V" chance="0.2" />
				< name="Flashlight" chance="0.2" />
		</cargo>
		<cargo chance="0.1" name="mixArmy">
				< name="SodaCan_Cola" chance="0.05" />
				< name="SodaCan_Pipsi" chance="0.05" />
				< name="SodaCan_Spite" chance="0.05" />
				< name="TunaCan" chance="0.1" />
				< name="SardinesCan" chance="0.05" />
				< name="CJ_Key3" chance="0.01" />
				< name="PeachesCan" chance="0.05" />
				< name="SpaghettiCan" chance="0.05" />
				< name="BakedBeansCan" chance="0.05" />
				< name="TacticalBaconCan" chance="0.1" />
				< name="Canteen" chance="0.1" />
				< name="Ammo_45ACP" chance="0.2" />
				< name="AmmoBox_45ACP_25Rnd" chance="0.05" />
				< name="Ammo_762x39" chance="0.2" />
				< name="AmmoBox_762x39_20Rnd" chance="0.05" />
				< name="Ammo_762x54" chance="0.2" />
				< name="AmmoBox_762x54_20Rnd" chance="0.05" />
		</cargo>