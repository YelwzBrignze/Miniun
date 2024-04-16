# Miniun
Just a difficulty change

{
		"name": "Coffee Hacienda",
		"uniqueTo": "Colombia",
		"terrainsCanBeBuiltOn": ["Hill"],
		"uniques": ["Can be built outside your borders","Provides [1] [Spices]",
			"Cannot be built on [Tundra] tiles","Cannot be built on [Snow] tiles","Cannot be built on [Desert] tiles","Does not need removal of [Jungle]",
			"Great Improvement","Will not be displayed in Civilopedia",
			"Pillaging this improvement yields approximately [+57 Gold]",
		]
	},
	{
		"name": "Vigilance Post",
		"uniqueTo": "El Salvador",
		"techRequired": "Economics",
		"replaces": "Fort",
		"gold": 2,
		"production": 1,
		"terrainsCanBeBuiltOn": ["Plains","Grassland","Hill","Forest","Jungle"],
		"turnsToBuild": 9,
		"uniques": ["Can be built outside your borders","Gives a defensive bonus of [25]%", "Adjacent enemy units ending their turn take [10] damage",
				"Costs [1] [Gold] per turn when in your territory"],
	},
	{
		"name": "Darien Gap",
		"uniqueTo": "Panama",
		"terrainsCanBeBuiltOn": ["Land"],
		"production": -2,
		"techRequired": "Agriculture",
		"uniques": ["Can be built outside your borders",
			"[+1 Food, +1 Culture] <after discovering [Pottery]>",
			"[+1 Science, +1 Culture] <after discovering [Scientific Theory]>",
			"Units ending their turn on this tile take 50 damage when healing",
			"All units must spend 3 extra movement points when inside the Darien Gap",
				"Unpillagable",
				"Can be built just outside your borders",
				"Great Improvement",
				"Cannot be built on [Desert] tiles", 
				"Cannot be built on [Tundra] tiles",
				"Does not need removal of [Jungle]",
				"Does not need removal of [Forest]",
				"Does not need removal of [Marsh]"
				],
		"civilopediaText": [
			{
				"text": "The Gap of Darien, located in our world where it forms the border of Colombia and Panama, has shaped the history of the isthmus so greatly, even before civilization. An indomitable strip of hills, jungles and mountains, full of dangerous animals and illnesses, the Gap is the great wall that separates Panama from the rest of the continent."
			}
		]
	},
	{
		"name": "Panama Canal",
		"uniqueTo": "Panama",
		"terrainsCanBeBuiltOn": ["Plains","Grassland","Desert","Hill","Forest","Jungle"],
		"uniques": ["[+1 Gold] for each adjacent [Coast]","Can be built outside your borders",
			"Cannot be built on [Tundra] tiles","Cannot be built on [Snow] tiles",
			"Removes removable features when built", "Costs [1] [Gold] per turn when in your territory",
			"Great Improvement","Will not be displayed in Civilopedia","Unpillagable","Irremovable"
		],
  {
		"name": "Asil",
		"adjective": ["Asili"],
		"cityStateType": "Industrial",
		"uniques": ["[+100]% Production when constructing [Worker] units [in capital]"],
		
		"declaringWar": "You leave us no choice. War it must be.",
		"attacked": "Very well, this shall not be forgotten.",
		"defeated": "The great things we'll about to create are gone.",
		"outerColor": [ 20,20,20],
		"innerColor": [189,99, 0],
		"cities": ["Asil"],
		"civilopediaText": [
			{"text": "A group of dwarfs inhabited in the historical region of Aaru on the Pangaea. it was incorporated into Polgar Sod'em after the political marriage between the Sodites Prince Yurrgin with the Asili Princess Disa."},
		]
	},
	{
		"name": "Canthyria",
		"adjective": ["Centaurs"],
		"cityStateType": "Industrial",
		"startBias": ["Plains"],
		"uniques": ["[+1] Movement <for [Land] units>"],
		
		"declaringWar": "You leave us no choice. War it must be.",
		"attacked": "A barbarian like you will never enough with just a horse. I am not a horse!",
		"defeated": "I don't like you, not from the beginning.",
		"outerColor": [ 20, 20, 20],
		"innerColor": [199,59,19],
		"cities": ["Canthyria"],
		"civilopediaText": [
			{"text": "A centaurs state inhabited the souteastern part of the Rain Forest. it was divided into two groups, one group remain in their home, while the other group joined Niranna after the marriage between Thanue and Araros son of Aratoros."},
		]
	},
	{
		"name": "Clockwerk",
		"adjective": ["Clockwerks"],
		"cityStateType": "Scientific",
		"uniques": ["[+1 Science] from all [Science] buildings"],
		
		"declaringWar": "You leave us no choice. War it must be.",
		"attacked": "Very well, this shall not be forgotten.",
		"defeated": "Guess I'll work for you then.",
		"outerColor": [ 20,20,20],
		"innerColor": [150,87,42],
		"cities": ["Clockwerk"],
		"civilopediaText": [
			{"text": "A human kingdom on the Tanait plains in the north-central part of Balvaria, bordered with the Berenger Kingdom to the North and the Duchy of Nas to the West. It was one of the founding members of the Aeyris Alliances."}
		]
	},
	{
		"name": "Dayne",
		"adjective": ["Daynian"],
		"cityStateType": "Industrial",
		"uniques": ["[-50]% construction time for [All] improvements"],
		
		"declaringWar": "You leave us no choice. War it must be.",
		"attacked": "Just because you can't pay me, you declare war on me?",
		"defeated": "Just take all of my slave, will you?",
		"outerColor": [ 20, 20, 20],
		"innerColor": [239,169,119],
		"cities": ["Dayne"],
		"civilopediaText": [
			{"text": "A human city-state on the Llotidea Continent. It was often involved in rivalry with the dwarven kingdom of Manthrill to the northwest and the Thallin Empire to the west. The kingdom fell after being attacked by Torakj."},
		]
	},
	{
		"name": "Kov",
		"adjective": ["Kobolds"],
		"cityStateType": "Scientific",
		"startBias": ["Hill"],
		"uniques": ["Gain a free [University] [in capital]"],
		
		"declaringWar": "You leave us no choice. War it must be.",
		"attacked": "Very well, this shall not be forgotten.",
		"defeated": "So what is the meaning of a miner?",
		"outerColor": [ 20,20,20],
		"innerColor": [150,87,42],
		"cities": ["Kov"]
	},
	{
		"name": "Rog",
		"adjective": ["Roge"],
		"cityStateType": "Scientic",
		"startBias": ["Jungle"],
		"uniques": ["All newly-trained [Melee] units [in capital] receive the [Charge] promotion"],
		
		"declaringWar": "Hungry ... hungry for eternity ...",
		"attacked": "I am hungry of a fresh flesh myself!",
		"defeated": "I hope you'll spare me your leftover to eat.",
		"outerColor": [ 20, 20, 20],
		"innerColor": [239,169,119],
		"cities": ["Rog"],
		"civilopediaText": [
			{"text": "Horde of ogre on the Balvaria. It helped Saeth of Tugu during the First Balvarian War."},
		]
	}
 {
		"name": "Cultural",
		"friendBonusUniques": [
			"[+3 Culture] <before the [Medieval era]>",
			"[+6 Culture] <starting from the [Medieval era]> <before the [Industrial era]>",
			"[+13 Culture] <starting from the [Industrial era]>"
		],
		"allyBonusUniques": [
			"[+6 Culture] <before the [Medieval era]>",
			"[+12 Culture] <starting from the [Medieval era]> <before the [Industrial era]>",
			"[+26 Culture] <starting from the [Industrial era]>",
			"[+2 Culture] [in capital]"
		],
		"color": [139,96,255]
	},
	{
		"name": "Maritime",
		"friendBonusUniques": [
			"[+2 Food] [in capital]"
		],
		"allyBonusUniques": [
			"[+2 Food] [in capital]",
			"[+1 Food] [in all cities]"
		],
		"color": [56,255,112]
	},
	{
		"name": "Mercantile",
		"friendBonusUniques": [
			"[+2 Gold] <before the [Medieval era]>",
			"[+4 Gold] <starting from the [Medieval era]> <before the [Industrial era]>",
			"[+8 Gold] <starting from the [Industrial era]>",
			"[+2 Happiness] <before the [Medieval era]>",
            "[+3 Happiness] <starting from the [Medieval era]>",
			"[+2 Happiness]"
		],
		"allyBonusUniques": [
			"[+2 Gold] <before the [Medieval era]>",
			"[+4 Gold] <starting from the [Medieval era]> <before the [Industrial era]>",
			"[+8 Gold] <starting from the [Industrial era]>",
			"[+2 Happiness] <before the [Medieval era]>",
            "[+3 Happiness] <starting from the [Medieval era]>",
			"Provides a unique luxury"
		],
		"color": [255,216,0]
	},
	{
		"name": "Militaristic",
		"friendBonusUniques": [
			"Provides military units every ≈[20] turns", 
			"[+4]% Production when constructing [Walls] buildings [in all cities]",
			"[+4]% Production when constructing [Castle] buildings [in all cities]",
			"[+4]% Production when constructing [Arsenal] buildings [in all cities]"
		],
		"allyBonusUniques": [
			"Provides military units every ≈[17] turns"
			"[+4]% Production when constructing [Walls] buildings [in all cities]",
			"[+4]% Production when constructing [Castle] buildings [in all cities]",
			"[+4]% Production when constructing [Arsenal] buildings [in all cities]"
		],
		"color": [255,0,0]
	},
	
	{
		"name": "Religious",
		"friendBonusUniques":  [
			"[+3 Faith] <before the [Medieval era]>",
			"[+6 Faith] <starting from the [Medieval era]> <before the [Industrial era]>",
			"[+13 Faith] <starting from the [Industrial era]>"
		],
		"allyBonusUniques":  [
			"[+6 Faith] <before the [Medieval era]>",
			"[+12 Faith] <starting from the [Medieval era]> <before the [Industrial era]>",
			"[+26 Faith] <starting from the [Industrial era]>"
		],
		"color": [255,255,255]
	}
	}
[
	{
		"name": "Industrial",
		"friendBonusUniques": [
			"[+2 Production] [in capital]"
		],
		"allyBonusUniques": [
			"[+2 Production] [in capital]",
			"[+1 Production] [in all cities]"
		],
		"color": [139,69,19]
	},
	
	{
		"name": "Scientific",
		"friendBonusUniques": [
			"[+3 Science] [in capital]"
		],
		"allyBonusUniques": [
			"[+3 Science] [in capital]",
			"[+2 Science] [in all cities]"
		],
		"color": [84,215,247]
	}
]
