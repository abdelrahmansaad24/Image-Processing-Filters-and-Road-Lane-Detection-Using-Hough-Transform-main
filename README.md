# Image-Processing-Filters-and-Road-Lane-Detection-Using-Hough-Transform
## Part I: Applying Image Processing Filters For Image Cartoonifying

In this part of the assignment we want to make the real-world images look like they are genuinely
from a cartoon. The basic idea is to fill the flat parts with some color and then draw thick
lines on the strong edges. In other words, the flat areas should become much more flat and the
edges should become much more distinct. We will detect edges and smooth the flat areas, then
draw enhanced edges back on top to produce a cartoon or comic book effect

## Part II: Road Lane Detection Using Hough Transform
The objective of this part of the assignment is the detection of road lanes in an image using
Hough Transform.

### Hough Transform
The Hough transform can be used to determine the parameters of a line when a number of
points that fall on it are known. The normal form of a line can be described with the following
equation: x cos θ + y sin θ = ρ where ρ is the length of a line that starts from the origin and
perpendicular to the required line, and θ is its inclination. The true parameters ρ and θ will
get maximum votes from the line points, and can be found with a Hough accumulation array
