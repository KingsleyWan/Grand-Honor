# Grand-Honor

<img width="250" alt="image" src="https://user-images.githubusercontent.com/105162197/192107190-8b3c34cd-f3df-4748-9a62-ad610ed04988.png">

## A 2D + 3D cross-platform game engine
Grand Honor is BCM new action game that target achiever game who fancy fantasy and winning.
Survive as much you can, defeat characters and opponents gain experience and earn gold, with experience used to unlock character's abilities or further augment the ability's power, and gold used to purchase items at the store, and upgrade/purchase new characters.


#### Message from Product team (Product Director) [04/08/2022]:
- Gameplay 2D/3D Artwork (visual elements)
- Storyboard narrative, directing player experience
- Include in-game feedback channel to facilitate player support.

# Project Team
<img width="817" alt="image" src="https://user-images.githubusercontent.com/105162197/192151192-665f57f4-5fa1-4e7e-bfa6-c1b5663d59b0.png">


## Gameplay design 

<img width="271" alt="image" src="https://user-images.githubusercontent.com/105162197/192110610-7f0281bf-433e-4305-9163-681986a749f0.png">

#### Message from Operation team (lead designer) [30/09/2022]:
> Next design update on: Alpha 3.6

## Notes:
- Xcode Version: <b>7.0 Beta 1</b>| Latest iOS: <b>16</b>
- Using Xcode's simulator will be a bit laggy. Use Device for best experience.
- Current version: <b>Alpha v3.5.3</b>.
- <b>*Best experience with iPhone X </b>
 
#### Message from developer lead [22/09/2022]:
> This week the team had attended many meetings, and due to lack of time, Some did not work on the monster class. I want to let all teams know that this project will delay for 2 days significantly since I am working on other projects but would be assigning some team members to promptly close the gaps.<Br>
I have received many private messages about using the source code, so I will use this place to answer it.<Br>
Since this is a new product, the core development members will authorize and promptly update the product owner and designers on the shared and source code. The main purpose of this project is to show what we can achieve the demand and expectation of our users on new game release.

### TODO list:
   - [✔️] Add Basic Magnetic Field on Characters - <b>27/09/2022</b>
   - [✔️] Replace regular monsters - <b>27/09/2022</b>
      - [✔️] Add new regular character sprites - <b>27/09/2022</b>
        - [✔️] lioner - <b>27/09/2022</b>
        - [✔️] Druid - <b>27/09/2022</b>
        - [✔️] Purpler - <b>27/09/2022</b>
        - [✔️] Blacker - <b>27/09/2022</b>
   - [*] Add new Monsters
     - [*] Add Treant Sprites
     - [] Add Class for Treant
     - [] Add Actions for Treant
   - [*] Re-work on difficulty over time
   
[*] = Working [✔️] = Done

### Future Implementations:
- #### About to join TODO List (Order does not matter):
   - [] Add new drops from monsters (diamonds, trophy... etc?)
      - [] Gems (Red, Green, Purple)
   - [] Add new map
   - [] Re-work drop system. 
   - [] Add chance to summon shiny regular monster. (They drop Power-Ups)
   - [] Add Power-Ups
      - [] Imune Item
      - [] Increase Fire Power
      - [] Double Shoot
- #### High Priority (Order does not matter):
   - [] Add Level&Exp System for Account
      - [] Customized UI Progress Bar
      - [] Show level on the Badge
      - [] Show Current Percentage on the Badge
    - [] Add Game Over Scene
- #### Low Priority (Order does not matter):
   - [] Add Purchase Character Function
   - [] Add Companions System (Each side with a small minion to assist you) - Sidekicks!
   - [] Add new effect for character's death
   - [] Add sound when Fireball is incoming
   - [] Kinky constant speed
   - [] Add Unit Test
   - [] Add Character unique skills
   - [] Add new FX for character's bullets

## Note: Each new feature moves from Low Priority -> High Priority -> Todo List. In short, low priority items will go up.

### Discovered Bugs:
- Alpha completely freeze itself when it kills the player

#### Note about bugs:
Unless it crashes the game. Above bugs are put in low priority to be fixed. 

### Main Accomplishments:
- [✔️] Add support for iPhone 8 plus, iPhone X, iPhone 11, iPhone 12, iPhone 13, iPhone 14 
- [✔️] Preload Textures
  - [✔️] Add progress bar
  - [✔️] Divide Atlas into smaller atlas
- [✔️] Coin System
- [✔️] Character Selection
  - [✔️] Alpha II
  - [✔️] Ceta
  - [✔️] Velta
  - [✔️] Kelta
- [✔️] Add Backup Logic
- [✔️] Add Progress Track
- [✔️] Add Singleton Global to access all Sprites
- [✔️] Add shader to fonts (OpenGL)
- [✔️] Remove Main.storyboard for faster build time
- [✔️] Add Bomber Monster in-game
- [✔️] Add Kinky Monster in-game - <b>26/9/2022</b>
  - [✔️] Add Kinky Monster Sprites
  - [✔️] Add Kinky Monster Actions
- [✔️] Add Labels in Character Selection - <b>26/09/2022</b>
- [✔️] Add particle effects when selecting character - <b>27/09/2022</b>
- [✔️] "Fix" and find a better logic for the top bar which displays account progress <b>27/09/2022</b>
- [✔️] Add customized font ttf for Gold Label with OpenGL shader <b>27/09/2022</b>
- [✔️] Re-implement logic to increase enemies' HP and Velocity over time  <b>27/09/2022</b>
- [✔️] Add new bullets for characters:
  - [✔️] Add Alpha Bullet Sprites <b> 26/09/2022 </b>
  - [✔️] Add Ceta Bullet Sprites <b> 26/09/2022 </b>
  - [✔️] Add Velta Bullet Sprites <b> 26/09/2022 </b>
  - [✔️] Add Kelta Bullet Sprites <b> 26/09/2022 </b>
- [✔️] Add Class to create custom bullet sprite <b> 27/09/2022 </b>
  - [✔️] Add Bullet Power Logic - <b> 26/09/2022 </b>
  - [✔️] Add Upgrade Bullet Function - <b> 27/09/2022 </b>
  - [✔️] Add Upgrade Scene on Character Scene <b> 27/09/2022 </b>
- [✔️] Display current level of bullet and its image on Character Scene <b> 27/09/2022 </b>

