	
A remake of the game connections in Unity, made in a short amount of time with the goal of a steam release.

Main Concept
The same concept as the game design game, you connect multiple blocks to yourself.

Game Length
~ 1-2 hours depending on when I think I'm done.

Theming:
Nier Automata + Portal 2 + Overgrown Stone

sound design reference:
1: the original sound effects were good and people liked them
2: https://www.youtube.com/watch?v=-5rAjOjTGtc


2D.
it will be pixel art.
for some reason the original cube scaling on the pixels was not correct and you would need to fix that.
![[Pasted image 20250407214348.png]]

Box re-design?
Has panels that launch out the connected boxes, is also what you use to jump when your on the ground.
That means you can't jump when you have a box facing the ground without launching a cube.

First Level have normal boxes you can push around with your arrow keys that don't connect to you.

If 3d: visible Electromagnets and lights on each side, and a Circle Ejector Ring

Box features
Push on each side
Connect on each side.

lean in the direction of the mouse? Get an angle on your push if your on the floor?

No movement without treads attached on one side?
Slide On Electromagnetic Rail/Floor? Have sparks below. I like this.
WATER which you can always move a little bit in if you push

Lazy Eye (lazy in terms of mood not condition) looks in direction your pointing.

Room 1.
3 levels of height, your the highest on the right side of the screen where you activate. You can only push in all 4 directions to propel yourself.
You are in the corner so there is only the wall or floor to choose from.
When you do the wall, you fall down the "steps" and into a chute.
At the bottom of the chute is a production line.
You have to jump to avoid being crushed.
After the line you fall down into an 

Controls:
Launch connected Object WASD
Move on Electromagnetic Rail A/D (just make sure no connections on the rail or only one)
No connections On ground Lean Left and Right A/D
Launch Cube: S/Space?


Make tiles sets for broken down factory buildings.


Why is the game fun?
Puzzle platformer, same reasons as Celeste, quick restarts if you fail, and some level of thinking needed to beat the levels.
It will probably be a little slower than Celeste.


Mechanics wanted:
Rotate, shoot down, Rotate, shoot down etc. cross large horizontal gaps
Reconnect jump, if you launch from a cube the instant you connect with it, it does a much more powerful launch. (can't just hold the button though)

Buttons?
**Pros:** 
good for skill shots
**Cons:**
maybe too slow and puzzle depending on how used.

I think add buttons. You can add cool VFX around buttons too.

## Explaining every element of the game:

#### Player controls
SHIFT = rotate
SPACE = launch down. Those are confirmed
ESC = pause
TAB = eject all slots?
R = restart screen

#### Player Movement
Player movement is definitely going to be physics based.
The question is, are they allowed to move with no connections.
The options are:
Yes they slide like the prototype (idk)
No but they can launch and tilt launch
No unless they have a track attachment.

**I think I have the solution (!eureka!)**
When you use the arrow keys/WASD to move its very slow.
A bunch of sparks come out from behind you (yellow sparks)
BUT you can always launch at any time, with the tilting.
Tilting only works with the down direction
Then you can also have electromagnetic floors where you move fast (more sparks and blue sparks)

#### Camera
Camera movement, pretty much identical to how Celeste works.
camera transitions between screens.
Some sections will  follow the player with bounds set on the free axes.

#### Visuals
2D lighting and particle effects like you did in Godot.

Pixel art environment. A mix of tile sets for levels and background and also PNG sprites for decorations like vines you can place around.

The style is like Nier factories + overgrowth +


#### Level Data
As in, what data should make up a level?

Do we want one big scene or split it into areas. (kind of like Hollow Knight)
I think split it into areas that get loaded when the player is nearby.
So each area would contain, the scene with everything.
