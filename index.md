                                        # A journey for saving wild animals
                                                                                By:- Krishana Gyanwali & Sudesh Subedi

### Intial Idea: Rationale
* The initial idea was generated after discussing some issues which could help the users to understand the scenario by immersing in the environment. We wanted to create forest management to save wild animals referring to the California wildfire. The year 2020 does not only begin with Coronavirus but also the wildfires which killed millions of animals in Australia and the West coast of the United States. We wanted to create a forest which has not a tree in between and shallow lakes which animals can easily cross the water to reach the sandy island. The concept of the sandy island came into the picture because it would not burn by the fire or its flame. The objects on the island should not be destroyed by the fire. We wanted to give the message to the world through the players that it is the responsibility of humans to protect the wild animals. Wildfire is not always created by humans necessarily, sometimes,  some frictions in the atmosphere generate the fire especially in the summer season. We have drafted the blueprint. But, we were not able to portray everything in a short period.

* To ease the development work, the plan proceeded with designing the three different layers using Unity's open source and freely available 3D game kit. Each layer is explained below for the relevance of the game design.

### Challenges: 
It is impossible to create all these complex structures, environments, and animals in a short time. So, we drifted from the aboriginal idea, however, hypothetically (like sci-fi movie or anything could be possible kinda approach) we limit ourselves with the periphery of the original idea. But, the actual development of this game project took us in a direction where we learned a lot about Unity, C sharp language, and more importantly the 3D GAME Kit built by unity, a sophisticated gaming platform.

### Game Development

We have three layers in the game. The first layer is a simple layer in which some enemies block the saver (Ellen, the protagonist of Unity 3d Gamekit) to cross to the next level. The instruction is simple enough that Ellen has to find out the switch and jump the door or cross the door to go to the next level. The instruction pops up but not annoyingly on the scene during the time of the game. The second layer is more complicated and there are lots of enemies added and some of them are very powerful. The saver has to work hard to kill all the invaders, and then he has to cross the bridge and open the door to go to the next level, which means he saved the animals from those fireball throwing invaders.

Technically, it is depended on the UI design of multiple 3d platforms available in unity. The first two layers are dependent on 3D Gamekit as mentioned above. Layer 3 is dependent on Terrain tools-Fantasy land, animal prefabs (which we purchased from unity), and Fantasy skybox for sky bluish color. We manually created a terrain, added a wide pathway, the wide pathway is created because the intention is to cut off the fire from spreading to the next zone.

## Level 1st

As the picture below shows that we named our team as team 10: the saver, the main character in the game, Ellen. At first, Ellen is hidden in the ground. It was created like that because we planned to use the warning noise of wildfire to wake up the character. However, it became so complex to create waving sounds like the tornado warning and horrific atmospheres. We scrapped our project three times because it was breaking in some transition and the machine took so much time to process the data. So, we moved toward a simple game in which Ellen has to discover the switch to go to the next level. Around the switch area, enemies are added to prevent the character to enter the territory.

![image](https://github.com/kgyanwal/project2_final_level3/blob/master/img/layer1_image.png)

### Level 1st: Audio:

Audio is added to this layer to give some amusement to the scene and while playing it would add some excitement. Royalty-free audio is added to this layer. In the second level, we added audio initially and removed later on because the game is more intense.

### Technical description of Level 1: 

The whole game is created manually using the Unity 3D game kit. Initially, the terrain is created, then the 3D vegetation is added. We wanted to make an island for the same animals, so we created water around the surface. When Ellen sees the switch, she moves in that direction, the enemies attack. We gave a higher endurance number to the main character and one time hit to the enemies. So, Ellen has to kill the enemies to go to the next level. The spitter glues the character and runs away. Ellen has to follow and kill it to ease the transition to the next level. Once Ellen jumps over the door, the next level will start.

## Level 2nd

At this level, the character has more complicated structures to cross. When the character see the blue gate (teleporting), the character has to move towards that direction, there is some hidden puddle created, for which the character has to jump. The instruction to play the game is simple, the keyboard's up arrow to move forward, right to move right and left to left and back to back, and space bar for the jump. We used the default layout for the prompt because it is nicely finished, and the instruction is very straight forward. If we see in the picture below, there is a huge door, the character is hidden on the other side of the door, and she has to find the switch to go to the next level. Whenever the enemies encounter, the character has to kill.

![image](https://github.com/kgyanwal/project2_final_level3/blob/master/img/layer_2.png)

In this picture, the metallic enemies throw the fireball to spread the fire over the terrain. In between, we added an acid layer, if the character enters into that area it does, it became so hard to cross that area, at the same time, the enemy is attacking. We played more than 10 times to cross this area to find the key, then once we were succeeded. So, realizing that complexity we removed the acid layer from the death zone. That acid layer's color is changed to represent the lava.

In this level, more enemies are added including the fireball throwing creature, the character has to struggle a lot to kill it. We were successful to kill all enemies in once shot a couple of times, while capturing the video below, we had to play twice, we set up a time configuration that once the game restarts after the death of the player if the player moves within 10 seconds, the enemies killed in the prior incarnation are stilled in the killed state.

### Technical description of Level 2: 

Technically, this level is more challenging to create. As level 1, this level is also created manually. The structure of level 1 and level 2 is different. We added some custom functions of the C-sharp function where we have for the transition and have given some sensible names.  

## Level 3rd

This level is the first level we developed first, believing that we would move towards the next level by making sci-fi movie like game. We became over-ambitious as if we have the whole time to this project. Later, we realized that it is not doable with this limited amount of time. We were developing the plan B side by side. Then, eventually, we moved to plan B. Here, we delivered successfully. As level 1 and 2, this level is also created manually. In this layer, the animals thank Ellen for saving them, they jump and it feels like they are enjoying and dancing.

![image](https://github.com/kgyanwal/project2_final_level3/blob/master/img/final_layer.png)

The Alien creature is the one which planned to be used as a saver and that scares animals and animals will follow the designated route to save themselves. However, it ended up as the final picture of the project, as it is a happy ending for all animals. 


## The combined levels: Level 1, 2 and 3

The image below shows the pictorial description of levels 1, 2, and 3. All images above are compiled together to visualize in one place.

![image](https://github.com/kgyanwal/project2_final_level3/blob/master/img/p2.krishana_gyanwali.sudesh.png)

<div><img src="iimg/p2.krishana_gyanwali.sudesh.png" class="img-responsive" alt=""> </div>

## Project Structure:

![image](https://github.com/kgyanwal/project2_final_level3/blob/master/img/the_project_structure.png)

The picture above shows the structure of the project. All layers of the project are added into the Gameplay folder of the Unity 3D game kit. We compiled them here because it became easier for the transition. So, the layer_1 resembles level one of the game, layer_next2 is the second level in the game and the SampleScene is the third layer in the game. We also added two transition functions here because it was easier for us to edit and these functional components are associated with these layers.


## An example code snippet:

The following image shows the detailed project structure of level 1, which has all the elements assembled into the game of level 1. In the middle of the screen, it shows how the OnTrigger function works when there is any action occurs. We used a collider i.e. a box collider for the transition. And linked that box collider with the transition function. We put that box in the hidden position around the door, as soon as the main character enters that area, the next level game will start.

![image](https://github.com/kgyanwal/project2_final_level3/blob/master/img/code_snippet.png)


## Advantages

The advantage of this project implementation using a 3D game kit:
* It because it is easier to use and learn.
* It is an open-source library
* The developer can build on their custom environment, player, and objects
* It can be integrated with other libraries, we brought fantasy landscape built terrain to this environment
* Many games built using these tools are already on the production platform.

## Shortcomings

* It takes time to understand the whole concept of this library
* It has given the flexibility to create or add a custom function to build user defined action, which may not be easy for the game developers.
* It may not be compatible with some libraries

## Video Link:

## References:

* https://learn.unity.com/tutorials
* https://www.udemy.com/course/gamekit3d/?utm_source=adwords&utm_medium=udemyads&utm_campaign=Unity_v.PROF_la.EN_cc.US_ti.8154&utm_content=deal4584&utm_term=_._ag_83329501114_._ad_436603255162_._kw__._de_c_._dm__._pl__._ti_dsa-774930034729_._li_1026562_._pd__._&matchtype=b&gclid=Cj0KCQiAh4j-BRCsARIsAGeV12BYk9F9He-e2jbzqjV-12-lcaGzdRxAHeTkHVGPgp-5bbz447Lrei0aAj_gEALw_wcB
* https://assetstore.unity.com/packages/templates/tutorials/3d-game-kit-115747
* for Audio: https://www.storyblocks.com/audio/search?media-type=sound-effects&categories=nature
* https://assetstore.unity.com/packages/3d/environments/fantasy-landscape-103573
* https://assetstore.unity.com/packages/2d/textures-materials/sky/fantasy-skybox-free-18353


