BackEnd:
Extrair todos os Pokemon da listagem de 1 ~ 151
https://pokedex.org/#/pokemon/151


Exemplo da rota:
/pokemons/1
```json
{
    "id" : 1, 
    "name" : "Bulbasaur",
    "image" : "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png",    
    "types" : [
        {
            "name": "grass",
            "color" : "#DFDFDF" 
        },
        {
            "poison": "fire",
            "color" : "#121212" 
        }
    ],
    "weaknesses": [
        {
            "type" : "fire",
            "color" : "#DFDFDF" 
        },
        {
            "type" : "psychic",
            "color" : "#DFDFDF" 
        },
        {
            "type" : "flying",
            "color" : "#DFDFDF" 
        },
        {
            "type" : "ice",
            "color" : "#DFDFDF" 
        }
    ],
    "name" : "Bulbasaur",
    "level_evolution" : "16",
    "evolution": [
        {
            "id" : 2,
            "name" : "Ivysaur",
            "image" : "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/2.png",
        },
        {
            "id" : 3,
            "name" : "Venusaur",
            "image" : "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/3.png",
        }
    ],
    "natural_moves" : [
        {
            "name": "Leech seed",
            "color": "",
            "type": "grass",
            "description": "Plants a seed on the target that drains 1/8 of its max HP at the end of every turn and heals the user for the amount taken. Has no effect on grass Pokémon. The seed remains until the target leaves the field. The user takes damage instead of being healed if the target has liquid-ooze. rapid-spin will remove this effect. This effect is passed on by baton-pass."
        },
        {
            "name": "Growl",
            "type": "normal",
            "description": "Lowers the target's Attack by one stage."
        }
    ]
}
```



Referencia:
https://pokedex.org/
https://pokeapi.co/