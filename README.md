# Unreal Kitchen Project

**Unreal Kitchen Project** is my first VR project that I've built from scratch.
The player need to wash all dishes by putting them into the sink.
the more dishes you washed, the more they come.
try to wash more dishes as you can.
....
..
.
#### Controllers
- B for spawn the plate for fun before start / call menu
- A for click
- Grab for grab the plate
- START
- EXIT
- RESUME
- RESTART

## Details
#### The Design
- I have use the sphere instead of hands to minimize the project and its look nice
- kinda change it to Dark-Pink theme
- the place will be able to move after go into the sink (on purpose) because I think it feel better!
- however its will be removed from the level within the specific time
- just stand at the spawn point and you'll be able to reach for all the plates
- able to restart

#### Timing system (timer)
- Basically you start with a fixed amount of time
- after you washed a dish, you'll get some extra time
- you'll get lower rate of time depends on the amount of the dishes scores
- the game will end when the time reach 0
- the score is the number of dish you have washed

#### 3rd Party assets
- Sound and the room that come with the given package

## more details
- Unreal Enginw 4.15.3
- built for Oculus Rift
- 2 hand supported (2 motion controller)
- work well with one hand
- but not work very well yet?

## what to improve
- can't release two object from both hand at the same time
- not fully release object
- massive BP (it could be much less than this)
- some plates go through table
