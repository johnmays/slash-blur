# Slash-Blur

This repository contains Python code that implements an idea I had for a noisy blurring algorithm composed of many individual slices in random directions, which blur an image in the aggregate.  Right now, it is kind of slow. It could be highly optimized within Python alone using numpy and cython.  It could also probably be turned into a shader, however, its results are the product of a highly iterative algorithm, and how easy it would be to reproduce these results _without_ without completely sequential operations is unclear.  Here are the algorithm's results:

#### Original Image:
![Aphex Twin Logo](data/out/twin_original_crop.png)
### Blur 1:
![Blur 2 actually](data/out/twin_blur2_crop.png)
### Blur 2:
![Blur 3 actually](data/out/twin_blur3_crop.png)
