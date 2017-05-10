A few versions of spark effects created to learn a little about the HTML5 canvas element.

v1
My first attempt, its pretty rudimentary.

v2
My favourite out of the 3, hold the mouse button to spawn sparks, they bounce off of the walls, ceiling and floor.

v3
An attempt to improve over v2.
Motion blur in v2 is simulated using a background with a low alpha,
meaning that the background never fully goes black and thus residue/trails
from the previous particles are left over.
To get rid of this I used multiple canvas elements to simulate 'frames'.
The motion blur effect is an improvement over v2 however the colors are very faded,
and performance is very slow.
I know the issue but couldnt find a way to resolve it.
Might come back to it some time.
