# Searching Algorithms in AI
[Wikipedia Graph traversal](https://en.wikipedia.org/wiki/Graph_traversal)
Not going to get too into these, but the summary is:
* If you have a graph/tree of all possible world states, how can you find the path from the current state to a goal state.
	- For chess: What is the next move you should, given a certain current game state, to achieve a __winning__ game state.
* Different algorithms depending on what you're trying to find on the graph (minimum distance to another node, most paths that lead to a winning state, etc)

## Pros
* Compared to some other AI approaches, graph traversal is nice because it's very easy to introspective into why a certain output was produced. If something went wrong, you can trace it back to node and decision it went the wrong way.

## Cons
* Need to have a graph/tree in the first place.
	- What is the world state of a human-level intelligent chatbot?
* If the graph is too big, searching it becomes very painfuly. This is part of why making superhuman Go AIs couldn't be done with graph traverseal. There are simply too many possible game states.



