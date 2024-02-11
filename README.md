# Pokémon dataset
Pokémon included: 1025

Generations: 1-9

Features: 47

The dataset
---

| feature                  | data type | description                                                                                                                                                                          |
|--------------------------|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| dex_no                   | int       | National Pokédex number[^1]                                                                                                                                                              |
| name_en                  | string    | Name in English                                                                                                                                                                      |
| generation               | int       | Game generation the Pokémon was introduced (core series[^2])                                                                                                                             |
| forms                    | int       | Amount of different forms the Pokémon possesses[^3]                                                                                                                                      |
| category                 | string    | (Pokédex) category of the Pokémon                                                                                                                                                  |
| height_m                 | double    | Height in metres                                                                                                                                                                     |
| weight_kg                | double    | Weight in kilograms                                                                                                                                                                  |
| hatch_time               | int       | cycles[^4] before the Pokémon hatches from an egg                                                             |
| name_fr                  | string    | Name in French                                                                                                                                                                       |
| name_es                  | string    | Name in Spanish                                                                                                                                                                      |
| name_de                  | string    | Name in German                                                                                                                                                                       |
| name_it                  | string    | Name in Italian                                                                                                                                                                      |
| is_gendered              | bool      | Indicates whether the Pokémon has a specified gender                                                                                                                               |
| female_percent           | double    | Probability of encountering a female specimen, represented in percent                                                                                                                |
| male_percent             | double    | Probability of encountering a male specimen, represented in percent                                                                                                                  |
| is_breedable             | bool      | Indicates whether the Pokémon is capable of breeding                                                                                                                                |
| catch_rate               | int       | catch rate[^5] of the Pokémon                                                                                                                                                            |
| leveling_rate            | int       | category determining the amount of experience point needed for the Pokémon to level up[^6] |
| pokedex_colour           | string    | (body) colour of the Pokémon                                                          |
| base_friendship          | int       | friendship value[^7] set when this Pokémon is caught                                                              |
| base_hp                  | int       | base hitpoint value[^8]
| base_atk                 | int       | base attack value[^8]
| base_def                 | int       | base defense value[^8]
| base_spatk               | int       | base special attack value[^8]
| base_spdef               | int       | base special defense value[^8]
| base_speed               | int       | base speed value[^8]
| base_experience_yield    | int       | Base experience gained[^9] for defeating this Pokémon                                                                                                                                  
| egg_group_0              | string    | Category[^10] which determines the Pokémon this Pokémon can breed with                                                                                                                  |
| egg_group_1              | string    | Category[^10] which determines the Pokémon this Pokémon can breed with                                                                                                                    |
| type_0                   | string    | Type of the Pokémon                                                                                                                                                                 |
| type_1                   | string    | Type of the Pokémon                                                                                                                                                                  |
| ev_yield_hp              | int       | effort value/s[^11] for hitpoints gained by defeating this Pokémon                                                                                                                              |
| ev_yield_attack          | int       | effort value/s[^11] for attack gained by defeating this Pokémon                                                                                                                               |
| ev_yield_defense         | int       | effort value/s[^11] for defense gained by defeating this Pokémon                                                                                                                               |
| ev_yield_special_attack  | int       | effort value/s[^11] for special attack gained by defeating this Pokémon                                                                                                                               |
| ev_yield_special_defense | int       | effort value/s[^11] for special defence gained by defeating this Pokémon                                                                                                                               |
| ev_yield_speed           | int       | effort value/s[^11] for speed gained by defeating this Pokémon                                                                                                                               |
| description              | string    | Pokédex entry for this Pokédex                                                                                                                                                     |
| ability_0                | string    | The ability[^12] this Pokémon can have                                                                                                                                                   |
| ability_1                | string    | The ability[^12] this Pokémon can have                                                                                                                                                    |
| hidden_ability           | string    | The hidden ability[^13] this Pokémon can have                                                                                                                                             |
| is_legendary             | bool      | Indicates whether this Pokémon is part of the Legendary Pokémon category[^14][^17]                                                                                                           |
| is_mythical              | bool      | Indicates whether this Pokémon is part of the Mythical Pokémon category[^15][^17]                                                                                                              |
| is_part_of_evolution     | bool      | whether the Pokémon is part of an evolution[^18]                                                                                                                                          |
| stage                    | string    | indicates the evolution stage[^16] (`basic`, `stage 1` or `stage 2`)                                                                                                                      |
| evolution_level          | int       | indicates the level needed for the Pokémon to evolve                                                                                                                             |
| bulbapedia_link          | string    | link to the bulbapedia entry for this Pokémon                                                                                                                                        |

## further information
<small>_Created using data taken from: <a href="https://bulbapedia.bulbagarden.net/wiki/Main_Page">bulbapedia</a>, <a href="https://www.pokewiki.de/">pokewiki</a>, <a href="https://www.pokepedia.fr/">pokepedia</a>_

_Only the first/original form of every Pokémon is present in this dataset._


_latest update: 21.01.2024_</small>

[^1]: https://bulbapedia.bulbagarden.net/wiki/National_Pok%C3%A9dex
[^2]: https://bulbapedia.bulbagarden.net/wiki/Core_series
[^3]: https://bulbapedia.bulbagarden.net/wiki/Form
[^4]: https://bulbapedia.bulbagarden.net/wiki/Egg_cycle
[^5]: https://bulbapedia.bulbagarden.net/wiki/Catch_rate
[^6]: https://bulbapedia.bulbagarden.net/wiki/Experience#Relation_to_level
[^7]: https://bulbapedia.bulbagarden.net/wiki/Friendship
[^8]: https://bulbapedia.bulbagarden.net/wiki/Base_stats
[^9]: https://bulbapedia.bulbagarden.net/wiki/Experience#Experience_gain_in_battle
[^10]: https://bulbapedia.bulbagarden.net/wiki/Egg_Group
[^11]: https://bulbapedia.bulbagarden.net/wiki/Effort_values
[^12]: https://bulbapedia.bulbagarden.net/wiki/Ability
[^13]: https://bulbapedia.bulbagarden.net/wiki/Hidden_Ability
[^14]: https://bulbapedia.bulbagarden.net/wiki/Legendary_Pok%C3%A9mon
[^15]: https://bulbapedia.bulbagarden.net/wiki/Mythical_Pok%C3%A9mon
[^16]: https://bulbapedia.bulbagarden.net/wiki/Evolution#Evolutionary_families
[^17]: https://bulbapedia.bulbagarden.net/wiki/Terminology_of_Legendary_and_Mythical_Pok%C3%A9mon
[^18]: A Pokémon that is not part of an evolution in its original form will have `is_part_of_evolution==False` eventhough its regional form might be part of an evolution.
