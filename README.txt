Name-Suphia Aftab
Student ID-1001653924

Programming language-Java


The zip file contains four classes-
traversal, create_node, find_route and node_compare.
1.traversal class has two methods which handles uninformed and informed search.
2.create_node class contains information of each node in the graph.
3.find_route class finds the route between source and destination if it exists.
4.node_compare class sorts the frontier depending on the step cost.

Steps for execution-

1. First the below java files should be compiled on omega.
javac find_route.java
javac node_compare.java
javac create_node.java
javac traversal.java

2.The input1.txt and h_kassel.txt should be present in the directory.

3.The find_route method takes the command line arguments of input file, source and destination and the heuristic file(for Informed Seacrh)

4.To run the uninformed search type the below command on omega.
java find_route input1.txt Bremen Kassel
Output-
Nodes Expanded: 12
Distance: 297.0 km
Route :
BREMEN to HANNOVER 132.0
HANNOVER to KASSEL 165.0

java find_route input1.txt London Kassel
Output-
Nodes Expanded: 7
Distance: Infinity
Route :
None
As no path exists between London and Kassel.

5.To run the Informed search type the below command on omega.
java find_route input1.txt Bremen Kassel h_kassel.txt
Output-
Nodes Expanded: 3
Distance : 297.0 km
Route :
BREMEN to HANNOVER 132.0
HANNOVER to KASSEL 165.0

java find_route input1.txt London Kassel h_kassel.txt
Output:
Nodes Expanded: 7
Distance : Infinity
Route :
None
As no path exists between London and Kassel.








