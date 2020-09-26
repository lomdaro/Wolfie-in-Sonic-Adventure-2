### Wolfie in Sonic Adventure 2
## Inspiration
I was bouncing ideas with a friend of mine over Discord in order to find a great and funny idea we could pull off. My original idea was to do a sprite swap of Sonic with Wolfie, when my friend suggested a model swap of Sonic Adventure 2. With that, I got to work.
## What it does
Utilizing the SA2ModManager developed by Main Memory, users are able to download mods and place them in a mods folder for their PC copy of Sonic Adventure 2. With this tool, it's possible to load up this mod, allowing the player to control Wolfie the Seawolf in levels featuring Sonic as the playable character.
## How I built it
The model itself was co-developed by Colin Greeley, a freelance 3D Modeler that I'm close with. The model itself and rigging was made by him, and the implementation in game was done by myself. Colin created the model using Maya, and any alterations I had to do in 3ds Max 2021. Implementation was then done through various modding tools developed by Main Memory, known as "SA Tools."
## Challenges I ran into
The alterations of the model proved to be smooth in progress. However, the actual implementation is incredibly finicky. Modding tools for this game are still in their infancy, and as such models need to be altered in incredibly finite ways in order to get them to run in game. Recompiling .fbx files into the game's own ".sa2mdl" files requires making sure the models are lined up in the same ways, textures are loaded in a specific order, and certain rigs are placed at the exact same waypoints.
As such, their are still some serious bugs. For one, one of the eyes is actually floating in front of the model in game. Animations are bugged, as the rigging is not yet perfected. Finally, due to the nature of modding Sonic Adventure 2, the game has a tendency to crash periodically when loading Sonic levels.
## Accomplishments that I'm proud of
Not only am I incredibly proud of Colin's work towards making Wolfie fit the Sonic Adventure 2 world, I'm proud that the model itself managed to run in game. My concerns led me to begin developing a B plan in case it would be impossible.
## What I learned
As it turns out, modding games with very few tools and very little documentation proves to be really difficult! I learned more about this game's development than I would've ever have liked to.
## What's next for Wolfie in Sonic Adventure 2!
After the hackathon I will be updating the project so that Wolfie himself has a fixed eye and proper rigging. As for the crashes, I'll be looking into what can be done to avoid this in the future. In the meantime, I'm fairly happy with the end result, even if it's a bit of nightmare fuel.
# Wolfie-in-Sonic-Adventure-2
