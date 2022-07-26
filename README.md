# Abstract

The double-slit experiment is used to study the behavior of a single non-relativistic particle. To
simulate this experiment, we start by removing all dimensions from the Schrödinger equation. We
then discretize the equation according to the Crank-Nicolson approach. We initialize the simulation
with a Gaussian wave packet and a potential barrier given by the matrix $V$ . The potential barrier
can represent three different slit configurations. We use the Born rule to transform the Scr ̈odinger
equation to a probability function and visualize the change in the probability over time. Lastly, we
measure the particle using a detector screen at $x = 0.8$ and make a plot of the detection probability.
The single-slit configuration shows a Gaussian distribution, while both the double- and triple-slit
configurations show an interference pattern.

## Authors
- Sophus B Gullbekk (sophusbg@math.uio.no)
- Erlend Kristensen (erlek@math.uio.no)
- Tov Uberg Tyvold (tovut@math.uio.no)
- Jonathan Larsen (jonathel@math.uio.no) 


## Compile and run

To compile and run our code, in the file <code>src</code> write <code>$make</code>

## File structure

All the code for the project is located in the <code>src</code> folder.

The code for implementing the Wave simulation is located in the <code>WaveSim.cpp</code> and <code>WaveSim.hpp</code> files.

The code for generating results is located in the <code>main.cpp</code> file.

The code for plotting the figures used in the report is located in <code>plot.py</code>.

The data from our simulations is stored in the <code>textfiles</code> folder, where we have used <code>.bin</code> files for storage. 

We have also added a <code>animations</code> folder that contains interesting animations.
