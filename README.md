# D3_force_directed_graph
Force directed graph


Adding node labels: Modify graph.html to show a node label (the node name, i.e., the source) on the top right of each node. If a node is dragged, its label must move with it. 

Styling edges: Style the edges based on the “value” field in the links array. Assign the following styles:

If the value of the edge is equal to 0, the edge should be black, thin, and dashed.

If the value of the edge is equal to 1, the edge should be green, thick, and solid.

Scaling nodes: 

Scale the radius of each node in the graph based on the degree of the node (you may try linear or squared scale, but you are not limited to these choices). 

The degree of each node should be represented by varying colors. 

Pinning nodes (fixing node positions):

Modify the code so that when you double click a node, it pins the node’s position such that it will not be modified by the graph layout algorithm (note: pinned nodes can still be dragged around by the user but they will remain at their positions otherwise). Node pinning is an effective interaction technique to help users spatially organize nodes during graph exploration.

Mark pinned nodes to visually distinguish them from unpinned nodes, e.g., pinned nodes are shown in a different color, border thickness or visually annotated with an “asterisk” (*), etc.

Double clicking a pinned node unpins (unfreeze) its position and unmark it.

