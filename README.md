# SURGE
The large chemical and structural diversity of materials presents significant challenges in
discovering new materials with tailored properties for various applications. Material discovery
has traditionally progressed through expensive trial-and-error experimentation. Recent advances
in generative AI provide a promising approach to overcoming these challenges and accelerating
the discovery of new materials. Generative AI can discover new materials at a fraction of the cost
of experiments, vastly narrowing the material search space. Our project focuses on the generative
design of new molecules and materials with generative AI models.
We began by reviewing several existing approaches involving Generative Adversarial Networks
(GANs), Variational Autoencoders (VAEs), Large Language Models (LLMs), and Diffusion Models
applied to material and molecule generation. We subsequently identified a recent VAE-based
architecture that integrates Graph Convolutional Networks (GCNs) to generate drug-like
molecules. We have adapted this model for different molecule datasets, including QM9 (QM9
stands for Quantum Mechanics dataset with 9 properties, and it's a collection of approximately
134,000 small organic molecules) and AqSolDB dataset (AqSolDB is a curated dataset
of aqueous solubility values for 9,982 unique compounds). We are currently analyzing the
VAEs architecture and learning behavior for different dataset sizes and different types of
molecules.
Our immediate goal is to modify and train this model for the generation of crystalline
materials. The integration of graph-based neural networks with generative models offers a
promising pathway to learn the underlying structural distribution of complex molecules and
materials. Ongoing work includes customizing the model architecture and defining appropriate
graph representations for crystalline materi
