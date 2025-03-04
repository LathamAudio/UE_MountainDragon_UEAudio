![Third Person Project](https://www.lathamaudio.com/projects/images/0004-MoutainDragon/DragonCover2.png)

Have you watched & listened to 'How To Train Your Dragon' or 'Game of Thrones' and thought "I could do that!" Have you ever wanted to work on improving your creature design chops? Have you wanted to work on implementing your audio in the Unreal Engine with both Metasounds and Wwise to compare them? Are you me, because that is a very specific set of goals? Anyways, here is your chance!

This is the Mountain Dragon from the Quadraped Fantasy Creatures pack for the Unreal Engine, found on Fab.com. It comes as a set of creatures that have all the textures, animations, and skeletal mesh needed to get started but no audio! That's where we come in. I have set up the Mountain Dragon with basic movement, flying, and attack controls and setup the audio hooks to implement your own sound design. Follow the steps below to get started. 

# Setup
![Third Person Project](https://www.lathamaudio.com/projects/images/0004-MountainDragon/ThirdPersonProject.png)

## Install Unreal & Create Third Person Project
1. Download Unreal Engine 5.0 - 5.4 (dragon works in UE5.5 or less, but fireball particle only works in UE5.4 or less)
2. Open Unreal Engine
3. Create a new Third Person project
4. Close Unreal Engine
\
\
\
![Mountain Dragon](https://www.lathamaudio.com/projects/images/0004-MountainDragon/QuadrapedFantasyCreature.png)
## Install Pre-Requisites
1. From Fab.com download "**Quadraped Fantasy Creatures**" (This is the dragon)
	- https://www.fab.com/listings/52d686b6-1180-4f26-901f-ce3c69a14767

2. From Fab.com download "**Paragon: Minions**" (This is the fireball)
	- https://www.fab.com/listings/039ea035-9360-4e76-ad06-5d3a92da6f65

3. From Fab.com, download "**Realistic Starter VFX Pack Vol 2**" (This is fire & explosions)
	- https://www.fab.com/listings/ac2818b3-7d35-4cf5-a1af-cbf8ff5c61c1

4. In the Epic Launcher add the Quadraped Fantasy Creatures to your project
5. In the Epic Launcher add the Paragon: Minions to your project
6. In the Epic Launcher add the Realistic Starter VFX Pack Vol 2 to your project
  
![Mountain Dragon Github](/projects/images/0004-MountainDragon/MountainDragon_Github.png)
## Download Metasounds Audio Setup
1. Download "UE_MountainDragon_Audio-main.zip" from the LathamAudio Github using the green "<>Code" button
	- https://github.com/LathamAudio/UE_MountainDragon_Audio

2. Find the "MountainDragon" & "QuadrapedCreatures" folders in the downloaded .zip file and unzip them to the Content folder in your Unreal project overwriting any files

![Mountain Dragon Github](https://www.lathamaudio.com/projects/images/0004-MountainDragon/DefaultPawn.png)
## Setup Moutain Dragon Pawn
1. Open your Unreal project
2. In the Contnet Browser, open "BP_ThirdPersonGameMode" and change the Default Pawn to be "MountainDragon_BP"

## Controls
W - Move Foward\
S - Move Back\
A - Move Left\
D - Move Right\
E - Fly/Land\
Shift - Glide\
Left Click - Bite/Claw on Ground, Fireball in Air\
Righ Click - Breathe Fire

## Adding the Mountain Dragon to other maps
Now that we have a dragon that can walk, fly, attack, breathe fire, launch fireballs we don't just want to use the test third person map. The "Stylized Fantasy Provencal" level is an appropriate looking setting for testing out your dragon sound design.
1. From Fab.com download "**Stylized Fantasy Provencal**", and add it to your project
	- https://www.fab.com/listings/ced19ea1-31ed-437f-ae64-2b6b1561fede
2. Open the "Main" level located in "StylizedProvencal/Maps"
3. With the Default Pawn set in the Game Mode set you should be able to download envoronments from Fab.com and use the Mountain Dragon in all of them!

### Next up... working with Metasounds and Wwise to add your own sound design!

## If you have any questions contact me at: [chris@lathamaudio.com](mailto:chris@lathamaudio.com)
