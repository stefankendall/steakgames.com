+++
title = "start of a journey"
date = "2016-10-14T12:44:40-04:00"
draft = false

+++

Games are built in stages. In my case, the stages are like watching a belligerent duck stagger drunkenly across a gravel road.

<video style="width:100%" controls autoplay loop>
  <source src="/start-of-a-journey/demo.mp4" type="video/mp4">
</video>

This may *look* like a dumpster fire, but I'd consider it more of a controlled burn. It went something like this:

1. Apply force for movement. The player doesn't move, so jack up the power by a factor of 10,000.
2. The player collides with the sign right in front of it and rockets into space. 
That's pretty close but not exactly what I was looking for, so reduce the force and make the decoration layer non-collidable.
3. Crushed it. Commit. Push. Call it a night.

Aside from this obviously-flawless movement on iOS, there's a lot of stuff going on here beneath the eye.

# Layers

Every layer renders objects or a tileset, built with [Tiled](http://www.mapeditor.org/).
The whole level is a json export, so making levels is purely a creation effort with no manual coding.

# Behaviors

Enemies and tiles can have *behaviors* defined in the editor that I continue to make more complex.
 For example:
 
     delay 0.5 fly up 1 down 1
     
The more enemies and objects are driven by data, the easier it is to build and craft levels.
The goal is to build the engine and get the frack out of the way of level design.

# Movement

Almost all iOS games where you move in two-dimensions have **TERRIBLE** control schemes
 unless you bust out a $50 MFi controller and the game happens to support it.
 
# So what's next now that you've mastered all aspects of platformers?

Oh gosh! Thanks for the compliment. Well, I think the camera should probably follow the player.
That seems kind of important. Thanks for reading and STAY TUNED FOR MORE UPDATES!