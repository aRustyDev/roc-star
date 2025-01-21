# roc-star
A code property graph tool; taking lots of inspiration from Joern. But trying to make it more repeatable and more scalable.

> The origin of the name Roc Star is two parts
> 1. Roc is the language its written in
> 2. Star is short for starlings which are a bird that is commonly known to swarm, as a reference to the graph based nature of the tool.

## Components

1. API Server: Endpoints for Transforms, Import-Graph, & Export-Graph
2. Graph DB (`local: IndraDB`, `distributed: Quine`)
3. CLI: All-in-one GraphDB and Interactive tool for testing/deving/debugging
4. Schema-Registry: Holds schema for CPG
