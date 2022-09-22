# Kafka Streams Topology Visualizer

A tool helps visualizing stream topologies by generating nice looking diagrams from a kafka stream topology descriptions.

## [Try now](https://TekYin.github.io/kafka-streams-viz)

This was conceived during one of the lab days @ Zendesk Singapore.

Thanks to the following libraries
1. [Viz.js](https://github.com/mdaines/viz.js/) an emscripten built of Graphviz
2. [rough.js](https://github.com/pshihn/rough/) for generating hand-drawn like diagrams.

## Additional feature

Adding Firebase to save&load the topology

- open url with `?id=xxxxx` to try fetching the topology from Firebase
- if no `?id=xxxx` present, pressing `SAVE` will save the current topology and assigned to new id
- id there is `?id=xxx` present, pressing `SAVE` will update the value of the topology on that id