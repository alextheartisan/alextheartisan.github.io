---
tags: [ds, graph, index]
---

# Graph

Graph ($G$) is a structure containing vertices (or nodes) and edges (or links)

- Graph: $G$

Vertices have _degree_ or _valency_ -- number of edges coming out from this vertex.
_Leaf_ or _End vertex_ is a vertex with degree of 1.
_Isolated vertex_ is a vertex with degree of 0.

- Vertex: $u$
- Set of vertices: $V$

Edges can be _arcs_ or directed edges

- Edge: $(u, v)$, $(u, v, w)$ -- latter with weight
- Set of edges, arcs: $E$, $A$

## Properties

Graphs can be [[Graph orientation|oriented, unoriented or mixed]]

Graphs can be [[Graph cyclicity|cyclic or acyclic]]

Graphs can be [[Graph weight|weighted or unweighted]]

Graphs can be [[Graph connectivity|connected or disconnected]]

## Types

There are many _types_ of a graph such as [[Tree|tree]], [[Complete graph| complete graph]], etc

## Representations

Graph can be _represented_ in code as [[Adjacency matrix|adjacency matrix]], [[Adjacency list|adjacency list]], [[Edge list|edge list]]

## Operations

Edge contraction or Vertex involving, Vertex splitting, Graph union, [[Graph joining]], Graph product

## Traversals

Walk (Trail, Path), Cycle, Slef-loop

## Algorithms

Pathfinding, [[Depth-first search]], [[Breadth-first search]]

<!--
### Понятия
- !en[Подграф](Subgraph)
- !en[Плотность](Density)
	- !en[Плотный граф](Dense)
	- !en[Разреженный граф](Sparse)
- [[Notes graph]]

https://www.hackerearth.com/practice/algorithms/graphs/graph-representation/tutorial/
-->

---

- [Graph Theory](https://www.youtube.com/watch?v=09_LlHjoEiY) 📺
- [Some cool Graph game](http://pulzed.com/demo/tronix2/) 🎮

<!--

# Двудольный граф, биграф

aliases:
:::
Bipartite graph
:::

Все вершины двудольного графа можно разбить на две части, без граней между вершинами одной части

viz:
:::
graph {
	bgcolor = transparent
	arrowsize = .1
	node [
		shape     = circle
		width     = 0.1
		height    = 0.1
		fixedsize = true
		fontsize  = 0
		fillcolor = black
		style     = filled
	]
	edge [
		arrowsize = .6
		arrowhead = open
	]
	subgraph cluster_a {
		style = rounded
		color = lightgray
		a b c
	}
	subgraph cluster_b {
	  	style = rounded
		color = lightgray
		d e
	}
	{a b c} -- {d e}
}
:::

-->
