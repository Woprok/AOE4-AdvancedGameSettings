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
_Allows players to change relations during the game via Players & Tributes._
* Empowered King  
_King unit receives 4 additional active abilities: attack speed, production speed, attack damage, healing. Passive aura that boosts damage by 50% and 4 armor. Additional 800 health, 3.5 movement speed, 1 armor and 10 radius for vision._
* Tree Bombardment  
_Makes all siege and ships with attack ground able to destroy trees._
* Treasures  
_Search for small treasures around the map and claim them before your enemies._
* Double Production  
_Speeds up production and reduces cost of economic units to help establish strong economy faster._
* Handicaps  
_Provides percantage bonus to each player based on selected value. Economic bonuses are faster gather rates, larger carrying capacity and higher trade. Military bonuses include higher armor, health for all units and buildings. Buildings also receive higher production and research speed._
### Full Menu Preview
![image](https://user-images.githubusercontent.com/37557138/169667259-c9b3af09-d406-4e96-a2cb-9e5db00eb363.png)   
![image](https://user-images.githubusercontent.com/37557138/179069958-e119b2f6-58fe-478d-a361-64b16c09bb8e.png)    
Game mode that pitches players to fight without any civilization bonus. To obtain advantage players have to capture cities spread in a grid like shape around the map.
![image](https://user-images.githubusercontent.com/37557138/179069844-ef919d42-5225-467b-b775-57d0ad965999.png)   
Additional Options for Nomad AGS:
* Spawn Scout (Scattered)
_Spawns scout for scattered settlement start (classic nomad from AOE2). Available only in Nomad AGS._

![image](https://user-images.githubusercontent.com/37557138/179069811-aa982eea-47e1-47e8-8824-063706852409.png)    
Default game mode provided by this mod, provides almost all customization.
![image](https://user-images.githubusercontent.com/37557138/179068645-195cc617-dc53-47aa-b460-8d0ee02b3da2.png)   
![image](https://user-images.githubusercontent.com/37557138/179068717-7c699581-aba8-4763-9759-ed00f27f127f.png)   
![image](https://user-images.githubusercontent.com/37557138/179068770-711d5091-6901-496d-98bb-a54c17d05369.png)   
![image](https://user-images.githubusercontent.com/37557138/179069141-6fea89cb-5649-4ef9-8e27-df2678795731.png)   
![image](https://user-images.githubusercontent.com/37557138/179069268-743ee388-0920-4897-91f3-eecc6d49cf98.png)  
![image](https://user-images.githubusercontent.com/37557138/179069453-7febbf28-7d1d-4dde-83c3-fb0e90268351.png)  
![image](https://user-images.githubusercontent.com/37557138/179069611-81ccae9c-e95a-4121-9586-6a9678472879.png)   
  

## Feedback & Contribution & Donations:
Contribution in any form is welcomed. Let's built something great together :)   
Be free to also provide ideas or requests via issues/tickets.  
Donation link can be found in the side bar of this repository under "Sponsor this project".

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
Game has currently no dedicated API for AI as an result any issue related to AI behaviour can't be fixed. So any behaviour such as AI aging up even if players can't or AI being slower then expected to age up or play is out of reach to fix at the moment for a mod...
I suggest you to provide feedback to Relic, so they can improve AI or provide official API.  

#### King Unit
Currently there is issue where King is T-Posing on death. This issue can't be fixed in the mod as this is currently only Game Mode script.

## FAQ
* Can I use anything from this mod for another mod... ?  
Yes as long as you are doing more than minimal amount of changes or your mod isn't suitable to be add to Advanced Game Settings as an option.   
* I have this cool idea...  
Create ticket and we will see...
* Mod Localization to other languages  
If you can provide translation, it will be incorporated into the mod. Current english database is [here](https://github.com/Woprok/AOE4-AdvancedGameSettings/blob/master/assets/locdb/Advanced%20Game%20Settings_en.csv) If you want to test localization on local version of the mod you can use this [cheatsheet image to add entry to localization database.](https://github.com/Woprok/AOE4-AdvancedGameSettings/blob/master/resources/GUIDE%20TO%20NEW%20LOCALIZATION.png)
