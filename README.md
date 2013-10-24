
Text Only Planning of Cube2Mapping Vol2

-----------------------------


1. Introduction
    * What the heck is this all about?
    * What are the requirements?


2. Octal Editor
    * Get used to the cube
    * Different sizes
    * Know your limits - WTR

3. Layout
    * Game mechanics
    * Building on the grid
    * The building blocks of layouts
    * Go with the flow

4. Audiovisuals
    * Architecture
    * Immersion
        * Theme - The look and feel
        * Sound

5. Appendix
    * Know your resources


-----------------------------

#1. Introduction

##What the heck is this all about?

This book/guide/tutorial is about turning you into a level designer. People also prefer to say "Mapper" because in comparison, Cube2 aka 'Sauerbraten' does not come with as much features as Unreal Developer Kit or Farcry does. But Cube2 has his own idea of fun. What makes Sauerbraten so famous is its way to create worlds. Its Cooperative editmode, where you can create stuff simultaneously is very useful for being creative together. However, level design is not only a hobby, it is an occupation. All information you find in this guide may be applied on other games, I will however always include all essential information about how it's done in Cube2, and what about other games. The focus mainly relies on Cube2:Sauerbraten

This book will cover all the little secrets that you may wonder about: Why do some maps get played, others not? How are some levels fun while others are not fun to play? And eventually, why do some levels get into the next release and some not? Quadropolis is, a good place to start. It is a platform to rate and discuss about maps. If you think you got good material, thats the place to go.

##What are the requirements?

I will not tell you the very basics how to work with Cube2, this guide is for intermediate to expert creators. You should know your entities, how to modify them. How to texturize cubes and the different cubesizes. In the first chapter I will explain a few not so well known details about the cube. You will also need a lot of patience, as you need to get a feeling for whats good and whats not good to play.

#2. Octal Editor 

##Get used to the cube

If you are not familiar with how to handle cube formations and you got no workflow in texturizing

##Different sizes - use them

This belongs partly to chapter three - Layout.
There are different cubesizes which you can use for different tasks.

0
1
2 - Details
3 - Architecture
4 - Layout, Terrain
5 - Layout, Terrain
6
7
8
9

##Know your limits - WTR

#3. Layout

Creating a layout is the first step for beginning a project. You may have an idea in beforehand about the theme, look or feel, but it is by no means mandatory.
Some of my casual created maps that had no theme or concept intended became a Deathmatch map. It is very flexible, depending on how the map works without any details or color. We will go through the creation step by step. We have to know a few little things before we get started.

##Game mechanics

Every game has its unique set of rules. Consisting out of some constants like gravity, gamespeed, jumpheight and other stuff that creates the concept of the game itself. So unfortunatly you can't just make up your own rules in your world, you got to adapt to the existing gameplay and create layouts that utilize these constants. But there are a lot of other things that influence the gameplay. We have to take care of these entities, Which are weapons, different kinds of gamemodes, jumppads, teleports and a lot more. We will discover later what exactly can make or create a layout.  

Sauerbraten got a very fast gameplay. It is hard to create a Battlefield-similar game experience. Instead, Sauerbraten is known for its need for quick reflexes. Having enough room is important. Talking about every single room or corridor within the level.

##Building on the grid

As we covered the different cubesizes and their use before, you may wonder why exactly the size 4 and 5 should be used for layouts.

First of all: it is about mathematics. You can jump a specific height, run at a specific velocity, etc. I have no idea if this was actually on purpose by the creator, but it seems to be that creating gaps with a 5-sized cube is just about the right distance a player can safely jump. Creating other layout elements such as stairs, just go right with this size. This doesn't mean that you have to create every single pathway just a cube wide, having variation is very important. To sum up this chapter: building on the grid saves you time to get a proper layout working without caring too much about the detail. You do not want to throw away a fully detailed and texturized work, so make sure that the layout works before getting on that.

##The building-blocks of layouts 

We just cover the things here, that a layout should only contain before getting into detail.

Stairs/Ramps,
Podests,
Jumppads,
Dropoffs,
Teleports,
Obstacles or Stuff to hide (TO AVOID)
Terrain,
Others: Ladders, Ropes, 

These define a multiple of 
Open Areas,
Hallways,

##Go with the flow

This is something a guy called Redon teached me, when I was not quite sure about my first released map called Arabic.
He showed me that I should place things in the way where the player would walk next. This sounded a bit unreasonable yet because I thought that I want to challenge the player a bit where he got to hide or place his foots. However, I found out very fast that having the ability to expect how the layout will go, will increase the fun in playing it. Flow is what you call when you run and jump without bumping into walls. Make sure to playtest every bit of your layout 

##Where to start?

The worst thing how you could get started is to create yourself a border. Basically a /newmap will already give you a box-shaped place to edit so what should we do? First: You never know how big a map could possibly become. This is what a lot of beginners are not capable of: expanding when they need to. Most newbies will happily work within the same border without ever emerging to greater layouts whenever it would fit. Again: it is not about how big it is, but think out of the box when you see how things could be done. Most try to work within a boxshaped map and do not dare to break through these walls, even if it would go with the gameflow. It takes some creativity to get started and there are several methods to start with nothing.

Do not have your layout necessarely bound to a specific theme. If you plan to do, for example an egypt map, think about how fitting would be a clichee like a pyramid, but it wont really be playable if you just place a few pyramids. Which is why we choose to think about the theme later, even if there are some typical elements for specific themes. It is good to know them but right now they are not helping us to create something playable. Create yourself a set of stairs and place it somewhere, add Even if you try to start out small, you got to begin somewhere. 


---
Sidenotes for later:
List of smart placed trickjumps w/o rewards.

Healthboost under a level, you got to die to get it.
