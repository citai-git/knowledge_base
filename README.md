# Welcome to the CitAI knowledge base

## Table of contents
### In this markdown file:
* [Artificial general intelligence](#artificial-general-intelligence)
* [Associative learning](#associative-learning)
* [Category theory in AI](#category-theory-in-ai)
* [Deep learning](#deep-learning)
* [Free Energy principle](#free-energy-principle)
* [Medical imaging](#medical-imaging)
* [Reinforcement learning](#reinforcement-learning)
* [Representation learning](#representation-learning)
* [Statistical methods in AI](#statistical-methods-in-ai)

### In other markdown files:
* [Maths resources](./Knowledge/maths.md)
    * Category theory
    * Grouplike structures


* [Conference papers (to be sorted)](./Knowledge/conference-papers.md)
    * Neurips2020


<a name="artificial_general_intelligence"/></a>
## Artificial general intelligence





<a name="associative-learning"/></a>
## Associative learning







<a name="category-theory-in-ai"/></a>
## Category theory in AI







<a name="deep-learning"/></a>
## Deep learning





<a name="free-energy-principle"/></a>
## Free Energy Principle

### [Action and Perception as Divergence Minimization](https://arxiv.org/abs/2009.01791)

**authors:** Danijar Hafner, Pedro A. Ortega, Jimmy Ba, Thomas Parr, Karl Friston, Nicolas Heess.

**year:** 2020.

**abstract:** We introduce a unified objective for action and perception of intelligent agents. Extending representation learning and control, we minimize the joint divergence between the world and a target distribution. Intuitively, such agents use perception to align their beliefs with the world, and use actions to align the world with their beliefs. Minimizing the joint divergence to an expressive target maximizes the mutual information between the agent's representations and inputs, thus inferring representations that are informative of past inputs and exploring future inputs that are informative of the representations. This lets us derive intrinsic objectives, such as representation learning, information gain, empowerment, and skill discovery from minimal assumptions. Moreover, interpreting the target distribution as a latent variable model suggests expressive world models as a path toward highly adaptive agents that seek large niches in their environments, while rendering task rewards optional. The presented framework provides a common language for comparing a wide range of objectives, facilitates understanding of latent variables for decision making, and offers a recipe for designing novel objectives. We recommend deriving future agent objectives from the joint divergence to facilitate comparison, to point out the agent's target distribution, and to identify the intrinsic objective terms needed to reach that distribution.




<a name="medical-imaging"/></a>
## Medical imagining




<a name="reinforcement-learning"/></a>
## Reinforcement learning







<a name="representation-learning"/></a>
## Representation learning


### [Disentangling by Subspace Diffusion](https://arxiv.org/abs/2006.12982)

**authors:** David Pfau, Irina Higgins, Aleksandar Botev, Sébastien Racanière.

**year:** 2020.

**abstract:** We present a novel nonparametric algorithm for symmetry-based disentangling of data manifolds, the Geometric Manifold Component Estimator (GEOMANCER). GEOMANCER provides a partial answer to the question posed by Higgins et al. (2018): is it possible to learn how to factorize a Lie group solely from observations of the orbit of an object it acts on? We show that fully unsupervised factorization of a data manifold is possible if the true metric of the manifold is known and each factor manifold has nontrivial holonomy -- for example, rotation in 3D. Our algorithm works by estimating the subspaces that are invariant under random walk diffusion, giving an approximation to the de Rham decomposition from differential geometry. We demonstrate the efficacy of GEOMANCER on several complex synthetic manifolds. Our work reduces the question of whether unsupervised disentangling is possible to the question of whether unsupervised metric learning is possible, providing a unifying insight into the geometric nature of representation learning.


### [Learning Group Structure and Disentangled Representations of Dynamical Environments](https://arxiv.org/abs/2002.06991)

**authors:** Robin Quessard, Thomas D. Barrett, William R. Clements.

**year:** 2020.

**abstract:** Learning disentangled representations is a key step towards effectively discovering and modelling the underlying structure of environments. In the natural sciences, physics has found great success by describing the universe in terms of symmetry preserving transformations. Inspired by this formalism, we propose a framework, built upon the theory of group representation, for learning representations of a dynamical environment structured around the transformations that generate its evolution. Experimentally, we learn the structure of explicitly symmetric environments without supervision from observational data generated by sequential interactions. We further introduce an intuitive disentanglement regularisation to ensure the interpretability of the learnt representations. We show that our method enables accurate long-horizon predictions, and demonstrate a correlation between the quality of predictions and disentanglement in the latent space.


### [Symmetry-Based Disentangled Representation Learning requires Interaction with Environments](https://arxiv.org/abs/1904.00243)

**authors:** Hugo Caselles-Dupré, Michael Garcia-Ortiz, David Filliat.

**year:** 2019.

**abstract:** Finding a generally accepted formal definition of a disentangled representation in the context of an agent behaving in an environment is an important challenge towards the construction of data-efficient autonomous agents. Higgins et al. recently proposed Symmetry-Based Disentangled Representation Learning, a definition based on a characterization of symmetries in the environment using group theory. We build on their work and make observations, theoretical and empirical, that lead us to argue that Symmetry-Based Disentangled Representation Learning cannot only be based on static observations: agents should interact with the environment to discover its symmetries. Our experiments can be reproduced in Colab and the code is available on GitHub.


### [Towards a Definition of Disentangled Representations](https://arxiv.org/abs/1812.02230)

**authors:** Irina Higgins, David Amos, David Pfau, Sebastien Racaniere, Loic Matthey, Danilo Rezende, Alexander Lerchner.

**year:** 2018.

**abstract:** How can intelligent agents solve a diverse set of tasks in a data-efficient manner? The disentangled representation learning approach posits that such an agent would benefit from separating out (disentangling) the underlying structure of the world into disjoint parts of its representation. However, there is no generally agreed-upon definition of disentangling, not least because it is unclear how to formalise the notion of world structure beyond toy datasets with a known ground truth generative process. Here we propose that a principled solution to characterising disentangled representations can be found by focusing on the transformation properties of the world. In particular, we suggest that those transformations that change only some properties of the underlying world state, while leaving all other properties invariant, are what gives exploitable structure to any kind of data. Similar ideas have already been successfully applied in physics, where the study of symmetry transformations has revolutionised the understanding of the world structure. By connecting symmetry transformations to vector representations using the formalism of group and representation theory we arrive at the first formal definition of disentangled representations. Our new definition is in agreement with many of the current intuitions about disentangling, while also providing principled resolutions to a number of previous points of contention. While this work focuses on formally defining disentangling - as opposed to solving the learning problem - we believe that the shift in perspective to studying data transformations can stimulate the development of better representation learning algorithms.


<a name="statistical-methods-in-ai"/></a>
## Statistical methods in AI
