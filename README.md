# Inscribed Square Problem
This project utilizes a skeletal constraint-based search, a "rattling frame" to demonstrate that such a state of mechanical equilibrium exists for all continuous, non-self-intersecting 2D or 3D volumes. ( containing a regular triangle, square, regular tetrahedron and cube )

NOTE : The current visualisation uses a different more brute force method.

My proposed proof for the Inscribed Square Problem

Let C be any Jordan curve.

Let A and B be the minimum and maximum possible chord lengths across C.

Because A and B are non-zero and distinct, matching chord lengths are guaranteed to exist between them, covering 180 degrees of possible directions continuously.

Within any 180 degrees, every direction and its perpendicular both appear. By IVT (Intermediate Value Theorem), there must exist an angle at which a chord and its perpendicular chord are equal in length. Two equal perpendicular bisecting chords define a square. Therefore every Jordan curve contains an inscribed square.

A square is therefore a mechanical necessity of a continuous, non-self-intersecting loop.

IE : If you have two perpendicular chords going through any Jordan curve and you rotate them, while one gets longer or shorter, the other gets shorter or longer, making it a mechanical necessity that there is a matching pair somewhere around the Jordan curve.

![Inscribed Square Viewfinder Demo](viewfinder_demo.gif)

## Interactive Demonstration
You can view the **Inscribed Square & Cube Viewfinder** in action here:
[Run the Live Viewfinder](https://thor110.github.io/InscribedSquareProblem/)

Note that the viewfinders are merely demonstration while the shape and space finders more accurately showcase the method.

## Expansion Paradox
Consider a square expanding from any interior point within a Jordan curve. At a scale near zero, the square is entirely contained. At a scale larger than the curve's maximum diameter, the square entirely encloses the curve. Because the curve is a continuous, non-self-intersecting boundary, the transition from 'Inside' to 'Outside' necessitates an intermediate state where all four vertices intersect the boundary. Because the Jordan curve forbids self-intersection, this intersection cannot occur at a side length of zero, thereby guaranteeing a non-degenerate inscribed square.

## Inscribed Cube Problem
There exist planes whose intersection with any closed 3D Jordan surface is a Jordan curve, and those curves each contain an inscribed square, and the continuous variation of those squares across parallel planes guarantees a cube by IVT.

The resolution of the 2D Inscribed Square Problem provides a Deterministic Foundation for the 3D Inscribed Cube Problem.

By reducing the 3D volume to a continuous series of 2D planes, we can identify the cube as a mechanical necessity of the Jordan Surface.

## Inscribed Tetrahedron Problem
Just as a regular inscribed triangle is guaranteed to exist in any Jordan curve, I propose that a regular inscribed Tetrahedron is guaranteed to exist within any closed Jordan surface.