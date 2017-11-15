# Street-Mapping

This project has 8 files.
		LinkedList: Which from the linked list for the Hashtable
		Map: Which contains all the important methods like minimum spanning tree and dijkstra.
		Edge: Which represent the road themselves 
		Intersection: Represent the intersection
		Road: Represent road, so Edge Id and what it connects 
		Node: Which takes the edge and intersection
		GUI: Which draws the map
		main: Which runs the program.

The graphs is represented using hashMap of intersection and linked list. I decided to add the function that change how big the map should be depending upon the density of datas. The monroe.txt map has the concentration of the data meaning, if two points are too close to each other it’s hard to see the Red line which represents the shortest path between two points. The nys.txt has thousands and thousands of points and can also be represented in the GUI. 

Explanation of GUI: The GUI has three important colors,
				Red: Shows the shortest path between two requested points 
				Blue:Shows the Minimum spanning tree 
				White: Shows the road and intersection connections

How to run: The program accepts the command line 			
java ProgramName map.txt [-show] [-directions startIntersection
     				endIntersection] [-meridianmap]

		explanation: [-show] to show the map
			     [-directions startIntersection
     				endIntersection] defines the points for shortest path
				[-meridianmap] for minimum spanning tree

