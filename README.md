# Discord Vampire: The Masquerade (V5) RPBot

This is a simple Discord bot that contains simple commands for roleplaying via Discord.

## Install
1. `git clone` this repository, and browse to it from the command line
2. Run `yarn` to install `node_packages`
3. Run `yarn start --token=YOUR_TOKEN_HERE`

## Chat commands
| Command | Description |
| --- | --- |
| `!roll` | Rolls a given # of dice, and allows for hunger dice. |

### WoD Examples
 - `!dice 5` rolls 5 10-sided dice at difficulty 8.
 - `!dice 5@5` rolls 5 10-sided dice at difficulty 5.
 
 ### V5 Examples
 - `!roll-v5 4h2` rolls 4 10-sided dice, 2 of which are hunger dice.
 
 ### Chronicles of Darkness Examples
 - `!dice 5!!10` rolls 5 10-sided dice that explode on 10s.
 - `!dice 5!!9` rolles 5 10-sided dice that explode on 9s.
