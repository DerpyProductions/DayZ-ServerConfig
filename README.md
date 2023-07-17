# DayZ-ServerConfig

Config files for the DayZ Server

"[PVE] Surviving the Green Hell together |Zones|NoRaid|Expension"

IP: 51.195.8.21
Test Server: 51.195.96.217

WIP ...


ToDo:
- remove SNAFU weapons / mags etc. (old ones)
- add weapons damage Mod (after update)
- add race track (test bevorhand): dze loader mod needed
- AI loadout mmg green/olive & TAN (snafu)
- loadout SNAFU (specifie weapon sets)
- loot chest: add more cool weapons variants
- P2P trader: bug fixes, vehicle spawn positions?


restet Msg.
say -1 Server restart in 5 Minutes. Mod Update (RUS-Forma)
say -1 Server will restart now! Mod Update ...
say -1 Server will be back online in 5-10 Minutes



Info


Tutorial





MOD ID's:

@1559212036;@1564026768;@2545327648;@2572331007;@2116157322;@2793893086;@2792983824;@2831742849;@1932611410;@2536888090;@2443122116;@2663169692;@2950964578;@2800339728;@1832448183;@2860643107;@2921256386;@2827018523;@2345073965;@2976244400;@2977778411;@1646187754;@2982956046;@2651195301


<!-- .......................................... -->  
<!-- add to econemycore.xml  -->
<!-- .......................................... -->  
	<!-- ModExpansion Types -->
	<ce folder="expansion_ce">
		<file name="expansion_types.xml" type="types" />
		<file name="expansion_spawnabletypes.xml" type="spawnabletypes" />
		<file name="expansion_events.xml" type="events" />
	</ce>
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
		<file name="VT_Historical.xml" type="types" />
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
	<ce folder="db_custom">
	<!-- Mod Types -->
		<file name="BL_BoomLayThings_types.xml" type="types" />
		<file name="CJ_LootChest-CJ187_types.xml" type="types" />
		<file name="CJ_LootChest-CJ187_cfgspawnabletypes.xml" type="spawnabletypes" />
		<file name="CP_CannabisPlus_types.xml" type="types" />
		<file name="HeliPad_types.xml" type="types" />
		<file name="HM_Machines_types.xml" type="types" />
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

<!-- .......................................... -->  
<!-- add to cfg_eventspawns.xml  -->
<!-- .......................................... -->  
<!-- Copy from here... -->
	<!-- EXPANSION CARS -->
	<event name="VehicleUAZ">
		<!-- Airfield Vyvor -->
		<pos x="5419.167969" y="333.421509" z="9886.763672" a="178.721161" />
		<!-- Airfield Balota -->
		<pos x="4847.206055" y="10.586733" z="2465.876221" a="57.025002" />
		<!-- Military Base Tisy -->
		<pos x="1711.423950" y="453.369049" z="14120.800781" a="32.195831" />
		<!-- Military Base Kamensk -->
		<pos x="7743.189453" y="362.079010" z="14860.373047" a="15.953650" />
		<!-- Military Base Zeleno -->
		<pos x="2548.715088" y="191.960663" z="5198.598145" a="45.981197" />
		<!-- Military Base VMC -->
		<pos x="4544.528809" y="319.462463" z="8333.652344" a="26.989965" />
		<!-- Military Base Pavlovo -->
		<pos x="2209.268066" y="93.761986" z="3369.180420" a="45.016136" />
	</event>
	<event name="VehicleVodnik">
		<!-- Military Base Tisy -->
		<pos x="567.561096" y="503.953217" z="13655.631836" a="0.000000" />
		<!-- Plotina Tishina Dam -->
		<pos x="1159.035278" y="153.176682" z="6219.569824" a="0.000000" />
	</event>
	<event name="VehicleBus">
		<!-- Cherno Bus Station -->
		<pos x="6391.597168" y="12.033311" z="2696.855469" a="38.998974" />
		<!-- Elektro Bus Stop -->
		<pos x="10901.647461" y="5.876880" z="2813.317383" a="20.49" />
		<!-- Zeleno Bus Station -->
		<pos x="2514.898438 " y="190.492996" z="5272.000000" a="95.000023" />
		<!-- Pustoshka Bus Stop -->
		<pos x="2907.472412 " y="331.534241" z="7308.514160" a="17.00" />
		<!-- Servograd Bus Stop -->
		<pos x="7912.813965 " y="117.039627" z="12669.354492" a="64.00019" />
		<!-- Berezino Bus Stop -->
		<pos x="12982.299805 " y="6.062156" z="8363.116211" a="-17.00" />
	</event>
	<event name="VehicleTractor">
		<!-- Krasnostav -->
		<pos x="10869.070313" y="234.547668" z="12285.822266" a="37.827099" />
		<pos x="13465.051758" y="79.656189" z="13067.939453" a="325.00671" />
		<!-- Polyana -->
		<pos x="10665.547852" y="211.476746" z="7917.082031" a="289.703583" />
		<pos x="10785.945313" y="233.722229" z="8238.893555" a="164.680328" />
		<!-- Berezino -->
		<pos x="12300.703125" y="34.068638" z="9174.880859" a="0.000000" />
	</event>
	<event name="VehicleLandRover">
	    <!-- Stary Yar -->
		<pos x="4832.06" y="475.25" z="15187.4" a="-171"/>
        <!-- Metalurg -->
		<pos x="1052.22" y="159.931" z="6674.85" a="-90"/>
		<!-- Krasnostav -->
		<pos x="11164" y="197.614" z="12182.8" a="-58.5678"/>
		<!-- Youth Pioneer Camp -->
		<pos x="11151.7" y="134.596" z="7049.74" a="-110.19"/>
        <!-- Myshkino -->
		<pos x="2021.77" y="241.837" z="7054.07" a="-9.49191"/>
		<!-- Biathlon -->
		<pos x="503.831" y="424.199" z="11067" a="117"/>
		<!-- Dobroe -->
		<pos x="12865" y="63.4724" z="15123.1" a="32.4625"/>
	</event>
	<!-- EXPANSION HELICOPTERS -->
	<event name="VehicleMH6Helicopter">
		<!-- Airfield Vyvor -->
		<pos x="4169.207031" y="338.414795" z="10990.304688" a="71.035965" />
		<!-- Prison Island -->
		<pos x="2610.090576" y="21.751432" z="1306.517334" a="14.250560" />
		<!-- Military Base Tisy -->
		<pos x="1689.941284" y="451.738586" z="14343.285156" a="0.000000" />
	</event>
	<event name="VehicleMerlinHelicopter">
		<!-- Airfield Vyvor -->
		<pos x="4675.005859" y="342.870758" z="10362.887695" a="304.364269" />
	</event>
	<event name="VehicleUh1hHelicopter">
		<!-- Airfield Vybor -->
		<pos x="4096.730957" y="342.045197" z="10652.285156" a="26.790075" />
		<!-- Military Base Kamensk -->
		<pos x="8007.443848" y="342.698883" z="14627.948242" a="29.346302" />
		<!-- Biathlon Arena -->
		<pos x="504.444275" y="424.994934" z="11237.218750" a="10.636043" />
	</event>
	<event name="VehicleGyroHelicopter">
		<!-- Airfield Balota -->
		<pos x="5030.672363" y="9.536390" z="2356.444824" a="40.269878" />
	</event>
	<!-- EXPANSION BOATS -->
	<event name="VehicleUtilityBoat">
		<!-- Prison Island -->
		<pos x="2694.401367" y="2.893368" z="1386.396973" a="3.000063" />
		<!-- Balota -->
		<pos x="4324.443359" y="3.187644" z="2144.913818" a="285.999825" />
		<!-- Nizhneye -->
		<pos x="13078.616211" y="3.127557" z="8249.444336" a="94.973480" />
		<!-- Berezino -->
		<pos x="13222.479492" y="3.078305" z="9997.265625" a="195.999451" />
	</event>
	<event name="VehicleZodiacBoat">
		<!-- Kamenka -->
		<pos x="1862.077881" y="1.035321" z="2069.190430" a="119.000206" />
		<!-- Komarovo -->
		<pos x="3605.452881" y="1.037562" z="2051.242920" a="101.000137" />
		<!-- Prison Island -->
		<pos x="2828.842041" y="1.381267" z="1130.739990" a="120.687057" />
		<!-- Cherno -->
		<pos x="6857.394531" y="1.353274" z="2666.107422" a="0.000000" />
		<pos x="7004.533203" y="1.027294" z="2529.761475" a="235.000114" />
		<pos x="7504.036621" y="1.211231" z="2509.003906" a="25.000063" />
		<pos x="6463.131836" y="1.522734" z="2183.592773" a="132.766693" />
		<pos x="6570.701660" y="1.352989" z="2239.216797" a="83.193115" />
		<!-- Prigorodi -->
		<pos x="7793.382324" y="1.196902" z="2997.535400" a="202.000061" />
		<pos x="7806.783203" y="1.302303" z="2764.739014" a="244.647537" />
		<!-- Elektro -->
		<pos x="9798.750000" y="1.191982" z="1733.862427" a="135.000473" />
		<pos x="10190.645508" y="1.264722" z="1659.459717" a="80.000183" />
		<pos x="10892.398438" y="1.480017" z="2327.396973" a="0.000000" />
		<pos x="10950.109375" y="1.418841" z="2641.047852" a="55.000072" />
		<!-- Kamyshovo -->
		<pos x="12062.391602" y="1.077910" z="3420.425293" a="173.000580" />
		<!-- Near Solnechny -->
		<pos x="13472.156250" y="1.038827" z="5439.098145" a="0.000000" />
		<!-- Solnechny -->
		<pos x="13550.460938" y="1.387331" z="6299.495117" a="79.000191" />
		<!-- Nizhneye -->
		<pos x="13153.362305" y="1.107187" z="7669.155762" a="89.735107" />
		<!-- Svetlo -->
		<pos x="14297.227539" y="1.070972" z="13244.783203" a="261.999641" />
	</event>
	<!-- ....To here -->

 <event name="StaticContaminatedArea">
		<zone smin="0" smax="0" dmin="5" dmax="8" r="75" />
		<pos x="6034" z="7823" />
		<pos x="5045" z="9840" />
		<pos x="8496" z="13976" />
		<pos x="4903" z="5682" />
		<pos x="4009" z="11846" />
		<pos x="4124" z="10551" />
		<pos x="5344" z="9881" />
		<pos x="10415" z="8911" />
		<!-- <pos x="11876" z="12530" /> Heli Trader Krasno -->
		<pos x="3721" z="8920" />
		<pos x="6338" z="7800" />
		<pos x="4625" z="10467" />
		<pos x="1819" z="3452" />
		<pos x="4496" z="9625" />
		<pos x="2736" z="5377" />
		<pos x="2712" z="6758" />
		<pos x="4186" z="11041" />
		<pos x="10122" z="5490" />
		<pos x="1465" z="13645" />
		<pos x="4944" z="2460" />
		<pos x="4372" z="4643" />
		<pos x="9494" z="8820" />
		<pos x="3082" z="7979" />
		<!-- <pos x="3710" z="5993" /> Green Mountain-->
		<pos x="11507" z="14472" />
		<pos x="10942" z="13392" />
		<pos x="3339" z="15187" />
		<pos x="2722" z="9998" />
		<pos x="4965" z="15113" />
		<pos x="7955" z="14634" />
		<pos x="9555" z="13679" />
		<pos x="598" z="13669" />
		<pos x="8128" z="10955" />
		<pos x="5413" z="12606" />
		<pos x="1661" z="14346" />
		<pos x="1256" z="11449" />
		<pos x="3450" z="13016" />
		<pos x="5409" z="8539" />
		<pos x="3529" z="12545" />
		<pos x="7239" z="7012" />
		<pos x="10432" z="5978" />
		<pos x="4319" z="10174" />
		<pos x="748" z="1876" />
		<pos x="4761" z="6785" />
		<pos x="3656" z="2459" />
		<pos x="1910" z="2254" />
		<pos x="10698" z="8081" />
		<pos x="7097" z="12709" />
		<pos x="2509" z="5079" />
		<pos x="3681" z="14811" />
		<pos x="11211" z="12238" />
		<pos x="509" z="11089" />
		<pos x="5985" z="10342" />
		<pos x="4707" z="6365" />
		<pos x="4624" z="9603" />
		<pos x="6504" z="2749" />
		<pos x="341" z="9401" />
		<pos x="7254" z="3046" />
		<pos x="1143" z="2386" />
		<pos x="12195" z="13831" />
		<pos x="10996" z="12417" />
		<pos x="11800" z="14311" />
		<pos x="10432" z="9136" />
		<pos x="9559" z="11816" />
		<pos x="1484" z="11946" />
		<pos x="4531" z="8306" />
		<pos x="8093" z="9316" />
		<pos x="7177" z="7686" />
		<pos x="1157" z="7239" />
		<pos x="8175" z="12754" />
		<pos x="1427" z="14459" />
		<pos x="2835" z="12377" />
		<pos x="7702" z="12630" />
		<pos x="1686" z="14171" />
		<pos x="1554" z="13585" />
		<pos x="4338" z="13059" />
		<pos x="6666" z="14459" />
		<pos x="7817" z="14780" />
	</event>
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




