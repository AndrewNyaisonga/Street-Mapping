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

The graphs is represented using hashMap of intersection and linked list. The other methods and iterators are kept the same from the Labs. There is a lot of methods and variable names that I have taken them from the Weis book and some lab TAs. The Ur.txt map is so fast, but the map of it was so hard to implement mainly because it was too small. So I decided to add the function that change how big the map should be depending upon the density of datas. The monroe.txt map wasn’t too bad also but the concentration of the data means that if two points are too close to each other it’s hard to see the Red line which represents the shortest path between two points. The nys.txt takes up to 100seconds to load and display the minimum spanning tree, mainly because of the amount of data. 

Explanation of GUI: The GUI has three important colors,
				Red: Shows the shortest path between two requested points 
				Blue:Shows the Minimum spanning tree 
				White: Shows the road and intersection connections

How to run: As explained in the project requirements the program accepts the command line 			java ProgramName map.txt [-show] [-directions startIntersection
     				endIntersection] [-meridianmap]

		explanation: [-show] to show the map
			     [-directions startIntersection
     				endIntersection] defines the points for shortest path
				[-meridianmap] for minimum spanning tree

