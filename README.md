# ScienceU - Make It Matter: Exploring sustainable fuel options with computer simulations [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sedaoturak/ScienceU/Code_ScienceU.ipynb)

This tutorial was prepared to introduce materials modeling tools to high school students in the scope of [ScienceU - Make It Matter](https://science.psu.edu/outreach/scienceu/makeitmatter) camp at Penn State in 2023.

In the tutorial, students are expected to find alternative energy sources other than fossil fuels with the aim of decreasing CO<sub>2</sub> emisson. To do so, they calculate the energy content of certain hydrocarbons (methane, propane, octane), ethanol and hydrogen by using atomistic modelling and simulation method [DFT (Density Functional Theory)](https://en.wikipedia.org/wiki/Density_functional_theory).

For DFT simulations, [ase (Atomic Simulation Environment)](https://wiki.fysik.dtu.dk/ase/) and [GPAW (Grid-based Projector-Augmented Wave)](https://wiki.fysik.dtu.dk/gpaw/index.html) were used. The code was implemented on [Google Colab](https://colab.google/) in order for students to reach and use these modelling tools.

In the notebook of "[Code_ScienceU.ipynb](https://github.com/sedaoturak/ScienceU/blob/main/Code_ScienceU.ipynb)", they create molecules, visualize 3D model of the molecule, and perform the DFT calculations in addition to visualizing the electron density around the molecule.

After calculating the formation energy of each molecule, they are expected to calculate the energy of the combustion reaction. After all the calculations, they can plot the energy content per gram molecule vs. carbon content each in molecule to see which energy source would produce less CO<sub>2</sub> emisson while providing more energy.
