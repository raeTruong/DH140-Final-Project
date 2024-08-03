# Repository of PokéMetrics: Analyzing Stats and Type Effectiveness 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/raeTruong/DH140-Final-Project/HEAD) 
[![Link to Blog](https://badgen.net/badge/blog/website/yellow?icon=chrome)](https://raetruong.github.io/DH140-Final-Project-Blog/posts/pokemon_analysis.html) 
[![Blog Github](https://badgen.net/badge/blog/github/black?icon=github)](https://github.com/raeTruong/DH140-Final-Project-Blog)  
By Rachel Truong  

## Introduction
The Pokemon games are centered around battling others with a team of "pocket monsters," hence the name of the franchise. With a predetermined set of stats and moves for each of their monster partners, players direct their Pokemon in battle and struggle against other Pokemon trainers to make their way to becoming the champion of the Pokemon world. These stats and decisions ultimately become the deciding factor in who emerges victorious. Thus, it is important for players to understand the stats and inner mechanics of the game. However, the game is a gem of childhood for many, and as children, many had simply played the game without paying much attention to stats and numbers. Of course, the game is designed well and can be played as such, but having played the game in that manner, I struggled. My Pokemon were okay, but were never strong enough for my liking. Of course, having played for so long, I eventually figured out through trial and error which Pokemon were stronger than others, but playing more and more, I find that I still struggle with picking better Pokemon to use. 

### Motivation 
But now, equipped with time and data, I wanted to take the opportunity to do a data-driven approach towards analyzing the differences in strength between Pokémon through comparing their base stats. I've never done an in-depth analysis before, as I simply have just played the game and choosing Pokemon that I liked and thought would do the job. Just last week I was casually playing, but my pokemon kept dying on me right next to the entrance of the next town.

### Data Description and Source
For this project, I will be using PokeAPI, an API linked to multiple databases detailing everything about the Pokémon main game series. I will be specifically be using data from these databases: 
| Dataset | Description                                                                                         | Link                                           |
|---------|-----------------------------------------------------------------------------------------------------|------------------------------------------------|
| Pokemon | Database of all pokemon that exist in the game, as well as their stats                              | [API Docs](https://pokeapi.co/docs/v2#pokemon) | 
| Types   | Database of the pokemon types, and anything that relates to them (type effectiveness, Pokemon, etc) | [API Docs](https://pokeapi.co/docs/v2#types)   |

### Research Questions 
- Which type combination are good to have?
- Which Pokemon have the best stats?  
- What is the best Pokemon to carry on you when running into random Pokemon and enemy trainers?