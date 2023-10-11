# Stealth-Combat-System
![](https://github.com/revanthponna/Stealth-Combat-System/blob/master/trim2gif.gif)

- Designed and implemented a dynamic and immersive stealth combat system in Unreal Engine using Blueprints.
- Created separate player movement states such as jog, crouch, and prone, each with corresponding animations.
- I developed sophisticated enemy AI with precise patrol path following, enhancing gameplay realism and challenge by specifying path points for AI movement. The enemies can either end their patrol, continue looping on the same path or patrol back in reverse.

![](https://github.com/revanthponna/Stealth-Combat-System/blob/master/Screenshot%20(2).png)

- Utilized behavior trees and sequences to seamlessly manage and switch between different alert states of the enemy.
- Leveraged advanced AI perception systems in Unreal to create responsive enemy behaviors, including line-of-sight and noise detection, leading to dynamic player interactions.

![](https://github.com/revanthponna/Stealth-Combat-System/blob/master/trim1gif.gif)

- The enemies enter a caution state if a noise is detected, start searching the scene, and chase the player upon sight detection. If the player goes out of sight again, the enemy returns to the caution state and searches the last known player position.
- Finally, I created an intricate takedown mechanism, allowing players to execute stealth attacks from behind when in the crouching state.
