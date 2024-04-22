# Automatic Discovery of Visual Circuits
Code and data for the NeurIPS ATTRIB 2023 paper: Automatic Discovery of Visual Circuits

[Achyuta Rajaram](https://twitter.com/AchyutaBot)\*, [Neil Chowdhury](https://nchowdhury.com/)\*, <br>
[Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab/) , [Jacob Andreas](https://www.mit.edu/~jda/), [Sarah Schwettmann](https://cogconfluence.com) <br>
\*Equal contribution <br>

![Car Circuit Inception Teaser](/static/figures/car_circuit_inception_teaser.png)

**This repo is under active development, and the code and data will be released in the coming weeks. Sign up for updates by email using [this google form](https://forms.gle/PoJkZFLBRS2bh8Tx6).** <br> <br> 

To date, most discoveries of network subcomponents that implement human-interpretable computations in deep vision models have involved close study of single units and large amounts of human labor. We explore scalable methods for extracting the subgraph of a vision model’s computational graph that underlies recognition of a specific visual concept. We introduce a new method for identifying these subgraphs: specifying a visual concept using a few examples, and then tracing the interdependence of neuron activations across layers, or their _functional connectivity_. We find that our approach extracts circuits that causally affect model output, and that editing these circuits can defend large pretrained models from adversarial attacks. 
