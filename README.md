# C_Ray_Tracing

Practicing C on a Raytracing project using SDL2 library and by following [hirschdaniel's youtube tutorial](https://www.youtube.com/watch?v=2BLRLuczykM).

## Results

Following the implementation of [Daniel Hirsch](https://github.com/danieldeer), i was able to accomplish the same results as him in the manners of simulating the raytracing effect using C:

![raytracing](/assets/raytracing.gif)

As you can see, we can control our source of light position and the rays emitted by it are re-calculated and re-renderer.

## Limitations

Because we define the ray thickness and quantity using constants:

```c
#define RAYS_NUMBER 375
#define RAY_THICKNESS 1
```

And the logic behind the calculation of positions, angle and the proper rendering of rays is quite of a heavyweight, the more amount of rays, the program gets a lagging effect, but a better view of the raytracing. Anyways, this is a beautiful example of Raytracing and logic by Daniel.
