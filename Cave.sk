#=========================================#
#=====SK/PL WYKONANY PRZEZ THEFIGHTAZ=====#
#==========ZAKAZ KOPIOWANIA!==============#
#=========COPYRIGHT 2021©=================#
#=========================================#

#OPTIONS FOR SCRIPT
options:
	tag: &8&l[&2&lMc&6&lSquare&f&l.pl&8&l]

#VARIABLES FOR SCRIPT
variables:
	{wejscieKopalnia::%player%} = false
	{healthCrystal5} = 2500


#EVENTS ON REGION
on entering of region "kopalnia":
	set {wejscieKopalnia::%player%} to true
on exiting of region "kopalnia":
	set {wejscieKopalnia::%player%} to false
	
#EVENTS ON MINE
on mine gold ore:
	if {wejscieKopalnia::%player%} is true:
		set {zlotoWykopane::%player%} to 0
		if {zlotoWykopane::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone
			
			
#ON MINE COAL "WĘGIEL"		
on mine coal ore:
	if {wejscieKopalnia::%player%} is true:
		set {wegielWykopane::%player%} to 0
		if {wegielWykopane::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone
			
			
#ON MINE DIAMOND "DIAMENT"
on mine diamond ore:
	if {wejscieKopalnia::%player%} is true:
		set {diamentyWykopany::%player%} to 0
		if {diamentyWykopany::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone
			
			
#ON MINE EMERALD "EMERALD"
on mine emerald ore:
	if {wejscieKopalnia::%player%} is true:
		set {emeraldWykopany::%player%} to 0
		if {emeraldWykopany::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone

			
#ON MINE IRON "ZELAZO"
on mine iron ore:
	if {wejscieKopalnia::%player%} is true:
		set {zelazoWykopane::%player%} to 0
		if {zelazoWykopane::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone


#ON MINE REDSTONE "CZERWONY PROSZEK / REDSTONE"
on mine redstone ore:
	if {wejscieKopalnia::%player%} is true:
		set {redstoneWykopany::%player%} to 0
		if {redstoneWykopany::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone


#ON MINE LAPIS LAZULI "NIEBIESKI PROSZEK / LAPIS"
on mine lapis lazuli ore:
	if {wejscieKopalnia::%player%} is true:
		set {lapisWykopany::%player%} to 0
		if {lapisWykopany::%player%} is 0:
			set event-block to bedrock
			wait 5 seconds
			set event-block to stone

			
#ON MINE STONE "KAMIEN"
on mine stone:
	if {wejscieKopalnia::%player%} is true:
		chance of 3%:
			set event-block to gold ore
			set {zlotoWykopane::%player%} to 1
			stop
		chance of 2%:
			set event-block to diamond ore
			set {diamentyWykopane::%player%} to 1
			stop
		chance of 6%:
			set event-block to coal ore
			set {wegielWykopane::%player%} to 1
			stop
		chance of 4%:
			set event-block to emerald ore
			set {emeraldWykopany::%player%} to 1
			stop
		chance of 5%:
			set event-block to iron ore
			set {zelazoWykopane::%player%} to 1
			stop
		chance of 7%:
			set event-block to redstone ore
			set {redstoneWykopany::%player%} to 1
			stop
		chance of 4%:
			set event-block to lapis lazuli ore
			set {lapisWykopany::%player%} to 1
			stop
		chance of 100%:
			set event-block to stone
			set {stoneWykopany::%player%} to 1
			set {stoneWykopany::%player%} to 0
			if {stoneWykopany::%player%} is 0:
				set event-block to bedrock
				wait 5 seconds
				set event-block to stone
				stop
				
#EVENTS ON BREAK
on break gold ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break gold ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break gold ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is wooden pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break gold ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is stone pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
			
#-#
on break diamond ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break diamond ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break diamond ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is wooden pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break diamond ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is stone pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#-#
on break emerald ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break emerald ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break emerald ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is wooden pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break emerald ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is stone pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#-#
on break iron ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break iron ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break iron ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is wooden pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#-#
on break redstone ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break redstone ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break redstone ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is stone pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break redstone ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is wooden pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#-#
on break lapis lazuli ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break lapis lazuli ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break lapis lazuli ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is golden pickaxe:
			send "{@tag} &cNie mozesz tutaj uzywac &eZłotego kilofa! &8[&6Kopalnia&8]"
			cancel event
on break lapis lazuli ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is stone pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
on break lapis lazuli ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is wooden pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#-#
on break coal ore:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#-#
on break stone:
	if {wejscieKopalnia::%player%} is true:
		if player's tool is not pickaxe:
			send "{@tag} &7Uzyj odpowiedniego &6kilofa! &8[&6Kopalnia&8]"
			cancel event
#------------------------------------------------------------------------------------------------------------------------------------#
#BLOCK BLOCKS IN REGION "KOPALNIA"#

on break:
	if {wejscieKopalnia::%player%} is true:
		if event-block is spruce slab or iron bars or light gray carpet or glowstone or oak log or oak leaves  or jungle leaves or ladder or torch or vines or chain or hay bale or dirt or oak wood or grass or lantern or red concrete or orange stained glass pane or orange stained glass or red concrete powder or red wool or stone brick wall or red stained glass pane or red terracotta or bone block or dark oak leaves or gravel or acacia leaves or diorite or andesite: 
			send "{@tag} &7Na terenie &6Kopalni &7nie możesz niszczyć tych bloków! &8[&6Kopalnia&8]"
			cancel event
on damage of endercrystal:
	if attacker is player:
		remove damage from {healthCrystal5}
		send "{@tag} &7Pozostałe życie &b- &8[&6%{healthCrystal5}%&8]" to attacker
		cancel event
		if {healthCrystal5} is less or equal to 0:
			broadcast "{@tag} &4Boss &7w &eKopalni &7został &czabity!"
			kill victim
			create a safe explosion of force 2 at location of victim
			drop 15 diamond
			drop 2 obsidian
			drop 3 emerald
			wait 3600 seconds
			strike lightning effect at the victim
			summon endercrystal at {lokacjaCrystal}
			set {healthCrystal5} to 2500
			broadcast "{@tag} &4Boss &7w &eKopalni &7powstał ponownie!"
command /ustaw2 [<text>]:
	permission: ustaw
	trigger:
		if arg 1 is "item":
			set {lokacjaCrystal} to location of player
			send "{@tag} &7Ustawiono spawn krzystalu!"
			
		
	
