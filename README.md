# Pacman-CS373-AI
An academic exercise to help Pac-Man agent find paths through its maze world, both to reach a particular location and to collect food efficiently by building general search algorithms and applying them to Pac-Man scenarios.

To search with Depth-First Search, use the following commands:
* On Mac, use "python3"

python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent

The Pac-Man board will show an overlay of color for the states explored and the order in which they were explored (brighter red means earlier exploration)

To search with Breadth-First Search, use the following commands:
* On Mac, use "python3"

python pacman.py -l tinyMaze -p SearchAgent -a fn=bfs
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

