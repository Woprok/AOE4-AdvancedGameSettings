# AOE4-AdvancedGameSettings
Game mode for Age of Empires IV, that provides new options for players to customize their games. 

## Features:
* Regicide  
_Each player starts with a king unit and goal is to protect player's king and defeat all other kings._
* Score  
_Game lasts until timer reaches end or it was finished by any other win condition. Once timer reaches end, player with highest score will win._
* Conquest (Changed original Landmark)   
_Defines buildings that are used as objectives for victory. If all objectives are destroyed, once at least one was built, player will lose._
* Religious (Renamed original Sacred Site)
* Treaty  
_Game starts with predefined timer, during which all players are allied. Once timer ends relations will turn to original one._
* Settlement  
_Allows player to choose how they start/spawn into the game. Either with only units, units and town center or also with walls._
* Team Victory  
_Allows players to choose if game can be won as FFA, Team or with any dynamically formed team._
* Maintain Team Balance  
_Whenever team loses player, remaning players will share his population and resources._
* Team Solidarity  
_All players in team are elimianted if any of their teammates is eliminated._
* Enable AI Takeovers  
_Whenever player drops or rage quits from the game, he will be controlled by the AI for the rest of the match._
* Win Settings  
_Customize certain rules and values for win conditions such as timers._
* Team Vision  
_Changes how players vision is shared between allied players. Only team allies that can win together can share vision._
* Diplomacy  
_Allows players to change relations during the game._
* Tree Bombardment  
_Makes all siege and ships with attack ground able to destroy trees_
### Full Menu Preview
![image](https://user-images.githubusercontent.com/37557138/167272719-32d5087c-794f-46e9-8ec1-bf674c8b62ee.png)
![image](https://user-images.githubusercontent.com/37557138/167272731-036610fb-7021-4d34-89c8-879e684a22b4.png)
![image](https://user-images.githubusercontent.com/37557138/167272736-5b8b0890-e9f8-4255-8974-08ab9d034b9b.png)
![image](https://user-images.githubusercontent.com/37557138/167272744-1819f0c3-7e43-4a2f-9c55-a9fd2ae866eb.png)
![image](https://user-images.githubusercontent.com/37557138/167272748-28b8d81a-8e43-422a-8272-42dc51289a98.png)
![image](https://user-images.githubusercontent.com/37557138/167299668-dbd44689-99ed-4f45-bf29-d9f2784c4c84.png)

## Feedback & Contribution:
Contribution in any form is welcomed. Let's built something great together :)   
Be free to also provide ideas or requests via issues/tickets.  

## Bug & other issues:    
Include as much information as possible.   
Ideally all of the following:  
- Amount of PLAYERS & AI's and their teams.
- Map, seed, biome. 
- Tuning pack used.
- Options used in the match.  
- What happened before the crash or bug.  
- C:\Users\USERNAME\Documents\My Games\Age of Empires IV\LogFiles contains logs, in some cases they might contain additional information that might help for a problem to be resolved. Most informations are logged in scarlog and warnings.  

### Known Issues

#### AI
Game has currently no dedicated API for AI as an result any issue related to AI behaviour can't be fixed.
I suggest you to provide feedback to Relic, so they can improve AI or provide official API.

#### King Unit
Currently there is issue where King is T-Posing on death. This issue can't be fixed in the mod as this is currently only Game Mode script.

## FAQ
* Can I use anything from this mod for another mod... ?  
Yes as long as you are doing more than minimal amount of changes or your mod isn't suitable to be add to Advanced Game Settings as an option.   
* I have this cool idea...  
Create ticket and we will see...
* Mod Localization to other languages  
If you can provide translation, if will be incorporated into the mod. Current english database is [here](https://github.com/Woprok/AOE4-AdvancedGameSettings/blob/master/assets/locdb/Advanced%20Game%20Settings_en.csv)
