# Motion Estimation with Optical Flow

Below we dive into the fundamentals of Optical Flow,
look at some of its applications and implement two
main variants (sparse and dense).

## What is Optical Flow?

Optical flow is the motion of objects between consecutive
frames of sequence, caused by relative movement between the
object and camera.

## Sparse vs Dense Optical Flow

*Sparse optical flow* gives the flow vectors of key features
(i.e. few pixels depicting the edges or corners of an object)
within the frame. *Dense optical flow* gives the flow vectors
of the entire frame (all pixels) - up to one flow vector per pixel.
With this in mind, *dense optical flow* has a higher accuracy at
the cost of being more computationally expensive. 

![Sparse vs Dense Optical Flow](imgs/sparse-vs-dense.gif)