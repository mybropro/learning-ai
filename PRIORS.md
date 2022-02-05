# Priors
Here's what I know going into this. If your priors look similar, maybe you can take this ride with me.

## Definitions:
+ Artificial Intellignce (AI) - having a machine behave intelligently. Very broad definition, Atari computer bots might count as AI, as does HAL-9000.
+ Machine Learning (ML) - a process where a machine can learn how to behave intelligently. Can do this by showing examples, letting a machine iterate against a goal function, transfering from a similar problem, etc. 
+ Gradient Descent - this is a way to optimize a function to a local minimum. Ie "minimize the inaccuracy/loss of my `isCat()` detector". Seems like if you can provide a function, and a way to influence the loss (maybe by changing inputs a certain way, even if that way is unknown), you can spam changes until you see the loss go down. Continue this until you can't descend any more.
+ Neural Networks - A [graph](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)) where the edges between nodes are weighted. These weights are the important part of the network. "Good" weights are weights that produce the desired output given some input. Most of AI research is probably just figuring out what the proper shapes of thes graphs are, and how to determine the proper weights.
+ CNN/RNN/SegNets - These are types of neural networks. How they work is probably still all matrix multiplication, but the wiring between nodes, number of nodes, number of layers between inputs and output nodes is different. Why different models matters is unclear, maybe they trade-off cost for accuracy, or maybe some are better at some applications. Why there isn't just a general network that works best is unclear? CPU is to general purpose compute as `???` is to general purpose intelligence?
+ ML Model - this is a neural network that has been trained on data, and the weights are locked in. Basically this is just a series of nodes, the path that information travels through the nodes, and the fixed weights that need to be used for operations. This is cool because the only thing that is going to change once you have a model is the input data. There's probably lots of optimizations once you have this static model.

## Tools I've heard about:
+ PyTorch, Tensorflow, Keras, etc - frameworks for training + inferring models.
+ TPU, GPU, ASICs - compute for models. Practically this is very important because you need efficient compute if you want AI/ML to be practical.

## Relevant Educational Background:
+ 1 undergraduate physics program - Linear algebra, differential equations, complex analysis, stastical mechanics (which was mostly statistics)
+ 1 undegraduate computer science program - algorithms, data structures, information theory
+ Binge watching geohot videos

## Important Goals/Benchmarks in the field:
+ The [Hutter Prize](https://en.wikipedia.org/wiki/Hutter_Prize) - $$$ for improving text compression. Idea behind this is that basically AI is just compression. "Predicing which characters are most likely to occur next in a text sequence requires vast real-world knowledge" [+](https://en.wikipedia.org/wiki/Hutter_Prize#Goals). Not sure if I agree, but seems reasonable. [Kolmogorov complexity](https://en.wikipedia.org/wiki/Kolmogorov_complexity) is related to this, and that definitely makes sense.
+ MuZero - No prior knowledge given to model. The model was given an environment to play in, like a chess engine, and can play endlessly. It learns from this play, and can produce results that human players wouldn't expect. This seems like true learning, as opposed to mimicry.
+ GPT-3 - This is some sort of big web scraper that takes prompts and gives the likely response. No idea if they check syntax or how you setup a question answering model.
+ AlphaBlue - OG Chess AI that blew minds. Ended up not being the solution to AGI, but still monumental.

