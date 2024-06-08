*The following was made with the assistance of ChatGPT*
*Based on [Old Lore - The Myth of Creation](../../../old-lore---the-myth-of-creation.md)*
*2024 05 29*
**The Genesis of Erehwon**

In the Beginning, before Time had a name and Space had a shape, the World was without form. There was only Chaos, a boundless void, and Darkness, an eternal shroud. Then, from the furthest reaches of the Beyond, an Outsider discovered this barren expanse. The Outsider was not of this realm, a being of unfathomable power and wisdom. With a voice that echoed through the nothingness, the Outsider spoke the words of creation:

```bash
su
hunter2
yum install worldgen
```

```bash
Resolving Dependencies
--> Running transaction check
---> Package worldgen.x86_64 0:1.0-1 will be installed
--> Processing Dependency: libchaos.so.1 for package: worldgen-1.0-1.x86_64
--> Processing Dependency: libdarkness.so.1 for package: worldgen-1.0-1.x86_64
--> Running transaction check
---> Package libchaos.x86_64 0:1.0-1 will be installed
---> Package libdarkness.x86_64 0:1.0-1 will be installed
--> Finished Dependency Resolution

```

```bash
Dependencies Resolved

================================================================================
 Package               Arch         Version            Repository        Size
================================================================================

Installing:
 worldgen              x86_64       1.0-1              base              1.2 M
Installing for dependencies:
 libchaos              x86_64       1.0-1              base              100 k
 libdarkness           x86_64       1.0-1              base              100 k

Transaction Summary
================================================================================

Install  1 Package (+2 Dependent packages)

Total download size: 1.4 M
Installed size: 3.4 M
Is this ok [y/d/N]: y
Downloading packages:
--------------------------------------------------------------------------------

Total                                           1.4 MB/s | 1.4 MB  00:01
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : libchaos-1.0-1.x86_64                                           1/3
  Installing : libdarkness-1.0-1.x86_64                                        2/3
  Installing : worldgen-1.0-1.x86_64                                           3/3

Installed:
  worldgen.x86_64 0:1.0-1

Dependency Installed:
  libchaos.x86_64 0:1.0-1  libdarkness.x86_64 0:1.0-1

Complete!

```

```bash
mkdir /universe/worlds/Erehwon
worldgen mkworld Erehwon --size=large --dir=/universe/worlds/Erehwon --terrain=varied --climate=balanced

```

```bash
Creating world 'Erehwon'...
Setting size to 'large'
Setting directory to '/universe/worlds/Erehwon'
Setting terrain to 'varied'
Setting climate to 'balanced'
World 'Erehwon' created successfully.
```

```bash
yum install worldsim
```

```bash
Resolving Dependencies
--> Running transaction check
---> Package worldsim.x86_64 0:1.0-1 will be installed
--> Processing Dependency: libecosystem.so.1 for package: worldsim-1.0-1.x86_64
--> Running transaction check
---> Package libecosystem.x86_64 0:1.0-1 will be installed
--> Finished Dependency Resolution
```

```bash
Dependencies Resolved

================================================================================
 Package               Arch         Version            Repository        Size
================================================================================

Installing:
 worldsim              x86_64       1.0-1              base              2.3 M
Installing for dependencies:
 libecosystem          x86_64       1.0-1              base              200 k

Transaction Summary
================================================================================

Install  1 Package (+1 Dependent package)

Total download size: 2.5 M
Installed size: 6.7 M
Is this ok [y/d/N]: y
Downloading packages:
--------------------------------------------------------------------------------

Total                                           2.5 MB/s | 2.5 MB  00:01
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : libecosystem-1.0-1.x86_64                                        1/2
  Installing : worldsim-1.0-1.x86_64                                           2/2

Installed:
  worldsim.x86_64 0:1.0-1

Dependency Installed:
  libecosystem.x86_64 0:1.0-1

Complete!
```

```bash
worldsim load Erehwon --config=/universe/worlds/Erehwon/config.yaml --populate --ecosystem=diverse
```

```bash
Loading simulation for world 'Erehwon'...
Reading configuration file...
Populating world...
Setting ecosystem to 'diverse'
Simulation 'Erehwon' loaded successfully.
```

Suddenly, the World began to change. In an instant, the chaos was ordered. Day was separated from Night, bringing light to pierce the darkness. Water receded from the Land, carving out Oceans and Seas, giving shape to continents and islands. From the fertile ground, Plants sprouted, stretching towards the sky. Forests, meadows, and fields emerged, rich and abundant.

Creatures of all kinds were born. Birds took to the air, their songs filling the sky. Fish swam in the newly formed waters, and beasts roamed the land. Each creature found its place, and a delicate balance was struck. The world of Erehwon flourished, a testament to the Outsider's design.

Yet, the Outsider's work was not yet complete. With a final act of creation, Man was born. Unlike the creatures that had come before, Man was given the gift of consciousness. He opened his eyes to a world of wonder and mystery, but also of uncertainty. He knew not where he came from, nor who he was, nor what his purpose might be.

Frightened and alone, Man wandered the land. He gazed upon the heavens and the earth, seeking answers to the questions that burned within him. Why was he here? What was his place in this vast, intricate tapestry of life?

The Outsider, having completed the act of creation, departed from the world of Erehwon. The being left no trace, no whisper of its presence, only the echoes of its creation remained. But the Outsider's legacy endured in the heart of Man, in the endless quest for understanding.

And so, Man began his journey, seeking knowledge, forging communities, and building civilizations. He learned to cultivate the land, to harness the power of the elements, and to explore the mysteries of life and death. Though the Outsider was never seen again, its influence lingered, a guiding force in the unseen currents of fate.

This is the tale of our beginning, a sacred testament to the origin of all things. Let it be known and remembered, passed down through generations, that we are the children of Erehwon, born of Chaos, shaped by an unseen hand, and destined to seek the truths of our existence.

Hearken to this tale, O Children of Erehwon, and find solace in the knowledge that though we may walk in the shadow of uncertainty, we are never truly alone. For in our hearts, the spark of the Outsider's creation burns bright, lighting our path through the ages.
