# Dijkstra
Implementation of Dijkstra for a given obstacle map with dynamic start positions and goal positions.

Note:

1. 'dijkstra.mp4' is a short demo of how to use the script - 'dijkstra.py' with the input start position as (6,6) and (440,125), in the form of (x,y) coordinates
2. 'dijkstra.gif' is a GIF generated using the same inputs as the previous point. However it's in 60 FPS and hence is much smoother.
3. In the obstacle map shown in the matplotlib window, black color elements indicate actual obstacle locations, the small gray parts indicate the bloated portion of the obstacles and walls to accomodate the size of the obstacle.
4. When the explored nodes get plotted in the map, one can see that the gray colors showing the bloated walls getting smudged a bit - this is NOT because of nodes being explored in the obstacle regions but rather due to the size of the dots used for plotting the explored nodes. (smaller size made the explored portion look sparse due to low resolution)
