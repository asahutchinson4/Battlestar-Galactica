# Battlestar Galactica
 2D adaptation of episode 1 of the 90s Battlestar Galactica tv series. Made in UE4 using Blueprints.

# HIGH CONCEPT SUMMARY
Every 2 minutes and 16 seconds, an insurmountable enemy fleet warps in, bent on your destruction. 
You command a single ship, the only known survivor of a massive surprise alien attack on humanity. You 
must scavenge to manage both survival and growth in each sector you arrive in and jump out before the 
enemy catches you. You can risk just a few more seconds to gain an invaluable prize, in manpower, 
parts, fuel or even restoring a damaged ship to join your fleet. But hang around too long, and your shield 
will fail, and your fleet will be overwhelmed, fading into the stars along with the last of humanity.

# TEST PURPOSE
Evaluate a candidate’s ability to program systems, basic gameplay, and UI, within the framework of a 
simple proof of concept. This test will also provide the candidate with a chance to demonstrate design 
capability in terms of creating 1 undefined game system, as well as balancing and tuning all values and 
game feel. 

# TEST REQUIREMENTS
Implement a timer, and warp in enemy ships every 2 minutes and 16 seconds. Reset the timer when the 
player warps to the next sector.
Implement a very basic, randomized sector of space (just black screen is fine). There are only 3 things 
the player can collect or interact with in each Sector
*  Fuel – fuel is consumed when your ship moves. It’s consumed when jumping to a new 
Sector (a lot), and when moving around within a sector (a little).
*  Ships – When you interact with a Ship (takes time), it’s added to your fleet. Adding ships 
increases the max population you can hold. Adding a ship also increases the amount of 
fuel you need to move and jump. Adding a ship increases to your fleets Shields.
*  Escape Pods – When you interact with an escape pod, you add a random population to 
your fleet. You require ships to hold the population.


Implement a Player controlled Ship, which represents a fleet. If possible, each ship you collect gets 
added to the fleet as a smaller, following ship.


Implement an enemy fleet, which warps in and pursues your fleet. Your shields prevent a certain 
amount of damage until they are depleted.


Implement a very basic UI to show, Fuel, Ships and Population, and a “Jump” button.


Implement a win condition when the player reaches a population threshold.


Design and implement a random, and interesting adversity condition for the fleet as it progresses 
through sectors.

# TEST TIMEFRAME
1 Week. Art is provided
