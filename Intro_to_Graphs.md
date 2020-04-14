<a>https://www.youtube.com/watch?v=l2ei-74jviQ&feature=youtu.be</a>
beej

-   what graphs are
-   what they're made of
    -   nodes
    -   edges
    -   optional: weights added to the edges
-   what they represent
    -   collection of cites
        -   where roads are the edges
        -   social media connections

# Graphs I <a>https://www.youtube.com/watch?v=BK_8-XVp5XA&feature=youtu.be</a>

BFS (Breadth-First Search) - Algorithm used to search a graph

-   Explores all possible paths to find one with smallest weight, traversing across before traversing down.
-   Never revisits nodes

### Uses:

-   Mapping
-   Social networking

### The Algorithm:

1. Begin at the starting vertex(s)
2. Explore the vertex
   a. While +1 unscheduled vertices adjacent to current vertex
   i.schedule adjacent vertex to be explored
   [ queue ]
3. Mark vertex as explored ( remove from queue ) (First in First out)

-   Summary: BFS is good if solving a dericative of the 'shortest path' problem or other scenarios where you know the soultion is not far from the root.

# Graphs I <a>https://www.youtube.com/watch?v=VTLI7l-Ah-8&feature=youtu.be</a>

DFS (Depth-First Search) - Algorithm used to search a graph

-   Explores all possible paths to find on with smallest weight, traversing down a branch before traversing across the same level

Never revisists nodes

### Uses:

-   finding a solution to a problem where you know there is only one solution such as when mapping through a maze.

### The Algorithm:

1. Begin at the starting vertex(s)
2. Explore vertex
   a. If unexplored, adjacent vertex
   i. explore adjacent vertex
   b. Mark explored once all adfacent vertices have been explores ( remove from stack ) (Last in Last out)

-   Summary: DFS searches each branch to its deepest level before exploring another branch. This is good if you know the solution is very far from the root.
