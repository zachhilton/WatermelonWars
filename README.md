WATERMELON WARS

A fun tower defense game with procedurally generated levels and a variety of strategies

I did all the code for the project, and my friend did all the artwork. It was made in Unity Game Engine, and scripted in C#. It's our first game, so most of it is pretty standard stuff. It was a great opportunity to get familiar with Unity's potential.

The two things that I'm most proud of are the Moonshine Shack and the Procedurally Generated Levels. The Moonshine Shack does a bunch of iterations of a vector calculus algorithm I designed. First it estimates where the enemy will be by the time its molotov cocktail lands; from this it calculates what angle it should throw the molotov cocktail, and then inputs that back into the algorithm. After a lot of this recursive process, the error is small enough that the turret is rather precise. The Procedurally Generated Levels use Perlin noise to offset some waypoints, and then uses C1 continuous Bezier curves to make a pretty cool looking line that the bad guys walk on.
