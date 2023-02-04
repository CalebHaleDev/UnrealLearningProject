# UnrealLearningProject Overview

This is a basic game framework with demonstration of some features. I practiced moving the camera around the scene, moving and creating objects, applying and creating colors, textures, and materials (packaged formatting with color and texture options), adjusting the character view from third-person to first-person and changing the controls from world-relative to character-direction-relative (forward-backward rather than north-sound), creating a basic landscape, and making a display for player stats.

After hitting the arrow to run the game, you can use WASD to move and space to jump. I tried creating a sprinting feature with shift and could get directional movement, but not relative movement or quicker movement. This project was mostly just to learn the ins and outs of unreal engine and practice, so there's lots of little things I experimented with to see what it was like or how things worked.

Here is a short demo of the game being played and a walkthrough of the code:

[Software Demo Video](https://youtu.be/c-yYjjf84_A)

# Development Environment

I used Unreal Engine 5, with it's built-in blueprint system. While watching tutorials I learned about other resources that can work with Unreal Engine but I did not use any of them yet. C++ is also used with UE but I did not make any, anything that is used came with the basic settings and provided resources.


# Useful Websites

List of websites that I found helpful in this project:
* [UE5 documentation] (https://docs.unrealengine.com/5.1/en-US/)
* [Super nice, thorough UE5 tutorial] (https://www.youtube.com/watch?v=k-zMkzmduqI)

Less useful:
* [Playlist for beginners] (https://www.youtube.com/watch?v=bY6Nl-OEhSo&list=PLncmXJdh4q88DFCEVuGpOY3AGQwBvoQnh&index=4)
* [Playlist for FPS game]	(https://www.youtube.com/watch?v=iFu2WXc8lz0&list=PLL0cLF8gjBprG6487lxqSq-aEo6ZXLDLg&index=4)
* [playlist for UE5 misc] (https://www.youtube.com/watch?v=Eakt2hBd3YY&list=PLQN3U_-lMANNUTT77wEHBgAH8wywKJzjw&index=5)
* [Blueprints essentials course] (https://dev.epicgames.com/community/learning/courses/QGD/blueprints-essential-concepts/P7L/unreal-engine-introduction-to-blueprint-essential-concepts) seems cool, but is in UE4 I think
* [YouTube on Nanites] 	(https://www.youtube.com/watch?v=I_rHKEjajSc)


# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
* Change brick texture scaling (I did this previously, but a glitch reverted the changes. It may or may not be present in the final version)
* Add stats changing per tick (healing, and a damage-causing region)
* Add an item system and inventory (data types created, but no items or interfaces yet)
* Change personal character level and the game level (which map is active)
* Create other entities with behavior (passive or aggressive)
