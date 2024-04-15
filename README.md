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
	}
