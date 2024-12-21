# Civic_polisia
Additional tests of mored coded sophistication mod for Unciv

{
        "name": "Labor",
        "era": "Ancient era",
		"uniques": [
			"Adopt [Tribalism] <hidden from users>"
		],
        "policies": [
            {
                "name": "Serfdom",
                "uniques": [
					"Comment [Low Upkeep]",
					"[-1 Gold] per [6] population [in your cities]",
					"[+1 Gold] per [12] population [in your cities] <for [Organized] Civilizations>",

					"[+40]% weight to this choice for AI decisions",
					"[+20]% weight to this choice for AI decisions <when number of [Cities] is less than [4]>",

					"[-50]% construction time for [All] improvements",
                    "Only available <after discovering [Feudalism]>",

					"Unavailable <after adopting [Tribalism]> <hidden from users>",
					"Unavailable <after adopting [Slavery]> <hidden from users>",
					"Unavailable <after adopting [Caste System]> <hidden from users>",
					"Unavailable <after adopting [Emancipation]> <hidden from users>"
				],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 1,
                "column": 5
            },
            {
                "name": "Caste System",
                "uniques": [
					"Comment [Medium Upkeep]",
					"[-1 Gold] per [4] population [in your cities]",
					"[+1 Gold] per [8] population [in your cities] <for [Organized] Civilizations>",

					"[+50]% weight to this choice for AI decisions",

					// TODO: Unlimited number of artists/merchants/scientists
					"[+1 Production] from [Workshop] tiles [in your cities]",
                    "Only available <after discovering [Code of Laws]>",

					"Unavailable <after adopting [Tribalism]> <hidden from users>",
					"Unavailable <after adopting [Slavery]> <hidden from users>",
					"Unavailable <after adopting [Serfdom]> <hidden from users>",
					"Unavailable <after adopting [Emancipation]> <hidden from users>"
                ],
                "row":2,
                "column": 2
            },
                ],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 2,
                "column": 4
            },
			{
				"name": "Labor Complete",
				"uniques": [
					"Will not be displayed in Civilopedia",
					"Comment [Only able to select one civic at a time]"
				]
			}
        ]
    },
    {
        "name": "Economy",
        "era": "Ancient era",
		"uniques": [
			"Adopt [Decentralization] <hidden from users>"
		],
        "policies": [
            
            {
                "name": "Mercantilism",
                "uniques": [
					"Comment [Medium Upkeep]",
					"[-1 Gold] per [4] population [in your cities]",
					"[+1 Gold] per [8] population [in your cities] <for [Organized] Civilizations>",

					"[+20]% weight to this choice for AI decisions",

					// TODO: +1 Free Specialist in every city.
					"[+1 Gold] [in your cities]",
					"[+1 Science] [in your cities]",

					// No foreign trade routes except to vassals
					// Foreign corporations have no effect
                    "Only available <after discovering [Banking]>",

					"Unavailable <after adopting [Decentralization]> <hidden from users>",
					"Unavailable <after adopting [Free Market]> <hidden from users>",
					"Unavailable <after adopting [State Property]> <hidden from users>",
					"Unavailable <after adopting [Environmentalism]> <hidden from users>"
                ],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 1,
                "column": 3
            },
            {
                "name": "Free Market",
                "uniques": [
					"Comment [Medium Upkeep]",
					"[-1 Gold] per [4] population [in your cities]",
					"[+1 Gold] per [8] population [in your cities] <for [Organized] Civilizations>",

					"[+30]% weight to this choice for AI decisions",

					"[+1 Gold] from each Trade Route", // 1 trade route in every city
					"[+10]% [Gold] from Trade Routes",
					// -25% maintenance costs from corporations (BTS)
					"[-10]% maintenance cost for buildings [in your cities]",
                    "Only available <after discovering [Economics]>",

					"Unavailable <after adopting [Decentralization]> <hidden from users>",
					"Unavailable <after adopting [Mercantilism]> <hidden from users>",
					"Unavailable <after adopting [State Property]> <hidden from users>",
					"Unavailable <after adopting [Environmentalism]> <hidden from users>"
				],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 1,
                "column": 5
            },
            {
                "name": "State Property",
                "uniques": [
					"Comment [Low Upkeep]",
					"[-1 Gold] per [6] population [in your cities]",
					"[+1 Gold] per [12] population [in your cities] <for [Organized] Civilizations>",

					"[+60]% weight to this choice for AI decisions",

					// No maintenance costs from distance to palace
					"[-10]% maintenance cost for buildings [in your cities]",
					"[+1 Food] from [Workshop] tiles [in your cities]",
					"[+1 Food] from [Watermill] tiles [in your cities]",
					"[+10]% [Production] [in your cities]",
					// All corporations have no effect (BTS)
                    "Only available <after discovering [Communism]>",

					"Unavailable <after adopting [Decentralization]> <hidden from users>",
					"Unavailable <after adopting [Mercantilism]> <hidden from users>",
					"Unavailable <after adopting [Free Market]> <hidden from users>",
					"Unavailable <after adopting [Environmentalism]> <hidden from users>"
                ],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 2,
                "column": 2
            },
			{
				"name": "Economy Complete",
				"uniques": [
					"Will not be displayed in Civilopedia",
					"Comment [Only able to select one civic at a time]"
				]
			}
        ]
    },
    {
        "name": "Religion",
        "era": "Ancient era",
		"uniques": [
			"Adopt [Paganism] <hidden from users>"
		],
        "policies": [
            {
                "name": "Organized Religion",
                "uniques": [
					"Comment [High Upkeep]",
					"[-1 Gold] per [2] population [in your cities]",
					"[+1 Gold] per [4] population [in your cities] <for [Organized] Civilizations>",

					"[+20]% weight to this choice for AI decisions",

					"[+25]% [Production] <in cities following our religion>",
					// Organized Religion allows building Missionary without Monastery

					"Unavailable <before discovering [Monotheism]> <if [Shwedagon Paya] is not constructed>",

					"Unavailable <after adopting [Paganism]> <hidden from users>",
					"Unavailable <after adopting [Theocracy]> <hidden from users>",
					"Unavailable <after adopting [Pacifism]> <hidden from users>",
					"Unavailable <after adopting [Free Religion]> <hidden from users>"
                ],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 1,
                "column": 3
            },
            {
                "name": "Theocracy",
                "uniques": [
					"Comment [Medium Upkeep]",
					"[-1 Gold] per [4] population [in your cities]",
					"[+1 Gold] per [8] population [in your cities] <for [Organized] Civilizations>",

					"[+10]% weight to this choice for AI decisions",
					"[+50]% weight to this choice for AI decisions <when at war>",

					"New [Military] units start with [2] Experience [in cities following our religion]",
					// No non-state religion spreads

					"Unavailable <before discovering [Theology]> <if [Shwedagon Paya] is not constructed>",

					"Unavailable <after adopting [Paganism]> <hidden from users>",
					"Unavailable <after adopting [Organized Religion]> <hidden from users>",
					"Unavailable <after adopting [Pacifism]> <hidden from users>",
					"Unavailable <after adopting [Free Religion]> <hidden from users>"
				],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 1,
                "column": 5
            },
            {
                "name": "Free Religion",
                "uniques": [
					"Comment [Low Upkeep]",
					"[-1 Gold] per [6] population [in your cities]",
					"[+1 Gold] per [12] population [in your cities] <for [Organized] Civilizations>",

					"[+100]% weight to this choice for AI decisions",

					"[+10]% [Science] [in your cities]",
					"Unavailable <before discovering [Liberalism]> <if [Shwedagon Paya] is not constructed>",
					// "Only available <before founding a Pantheon>", // TODO: No state religion
					"[+1 Happiness] [in your cities]", // TODO:+1 Happiness per religion in a city

					"Unavailable <after adopting [Paganism]> <hidden from users>",
					"Unavailable <after adopting [Organized Religion]> <hidden from users>",
					"Unavailable <after adopting [Theocracy]> <hidden from users>",
					"Unavailable <after adopting [Pacifism]> <hidden from users>"
                ],
				"civilopediaText": [
					{
						"text": "Trigger Revolution to select a new Civic",
						"link": "Wonders/Revolution"
					}
				],
				"row": 2,
                "column": 4
            },
			{
				"name": "Religion Complete",
				"uniques": [
					"Will not be displayed in Civilopedia",
					"Comment [Only able to select one civic at a time]"
				]
			}
        ]
