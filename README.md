# BackEnd Pokemon 


## Objetivo
Criar um backend para ser consumido por qualquer aplicação Mobile.

## ToDo List:

- [ ] Extrair todos as imagens listagem de 1 ~ 151:  
Ex: 
```
https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png
https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/2.png
https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/3.png
...
```  
- [ ] Padronizar as cores: grass  
- [ ] Criar banco de dados para armazenar as infomações.  
- [ ] Permitirs CORs 
- [ ] Criar Swagger para uso da API-Restfull /docs 


## Testar localmente: 
Inicialmente você pode simular a API usando:  
```
npm install
npm run start
```
Assim é gerado uma API restfull:
Todos os Pokemons:
http://localhost:3000/pokemons

Listar informações do pokemon 1 `Bulbasaur`
http://localhost:3000/pokemons/1



### Exemplo de retorno:
Exemplo da rota:  
'/pokemons/1'
```json
{
    "id" : 1, 
    "name" : "Bulbasaur",
    "image" : "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png",
    "types" : [
        {
            "name": "grass",
            "color" : "#0ce850" 
        },
        {
            "poison": "fire",
            "color" : "#e80c0c" 
        }
    ],
    "weaknesses": [
        {
            "poison": "fire",
            "color" : "#e80c0c" 
        },
        {
            "type" : "psychic",
            "color" : "#615757" 
        },
        {
            "type" : "flying",
            "color" : "#94d1ef" 
        },
        {
            "type" : "ice",
            "color" : "#2d92c3" 
        }
    ],            
    "level_evolution" : "16",
    "evolution": [
        {
            "id" : 2,
            "name" : "Ivysaur",
            "image" : "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/2.png"
        },
        {
            "id" : 3,
            "name" : "Venusaur",
            "image" : "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/3.png"
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



## Referências:
https://pokedex.org/
https://pokeapi.co/