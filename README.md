# MP2_LevelDesign Design Doc

There are three parts to my level: the first island featuring a mansion/house to explore, a platforming section and a final small island with enemies.

On the first and last island, there is a barrier that prevents the player from continuing if their score is too low. This prevents players form speeding ahead and
encourages exploration to find collectibles/confront enemies. 

The first island is largely kept in a confined area, that prevents the player from using the flight mechanic. I took inspiration from Dan Cervak's preentation, where
he described how one design choice might be to have players unlock skills/powers as they progress through the game. While the player still has access to flight in
the first part, it will not do much good. Another addition to the level was the implemention of sections I call Downward Drafts, where there is a force pushing down
on the player whenever they are in flight mode. This prevents players from getting around the mansion, since they will not be able to reach the next part
without starting from a sufficient vantage point. The flight mechanic could still be used howver, to access areas of the map that are too high for jumps, so if the
player wants to experiment with flight, they will be rewarded.

The next part of the level is a platforming section with multiple smaller islands. The previous Downward Draft mechanic makes a return, because the provided character
mechanic of infinite flight would make for boring platforming. Now, the player has to time their jumps and switch to flight in order to have the max glide distance to
reach the next platforms. There are also powerups and enemies scattered here to add some challenge and incentive to go off the beaten path.

Finally there is the last, smaller island with enemies. They can try to knock the player off, which would likely cause problems since there are only a couple of
platforms around to catch the player. Thus, the stakes are higher to not get hit. Following a final score barrier, the player has a pretty straightforward path to the
goal.
