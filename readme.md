NEURON mod files for the K-DR current from the paper:
Skaliora, et al., Eur.J.Neurosci. 7:1558-1568 (1995).

- Running the kinetics.hoc simulation file will show 
the activation and inactivation steady-states, the time constants, 
and a family of curves generated modeling the same protocols 
used for Figs.4B of the paper.

- Parameters values are from postnatal cells, and markers show
the experimental values reported in the paper.
Note that the time constant of inactivation is faster in postnatal cells,
and m is plotted rather than m^3 for activation.

- The peak conductance has been adjusted to give approximately the
same peak currents shown in the experiments.
 
## Under unix systems:
to compile the mod files use the command 
``` nrnivmodl ```
and run the simulation hoc file with the command 
``` nrngui kinetics.hoc ```

## Under Windows using NEURON 5.1:
to compile the mod files use the ``` mknrndll ``` command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

\
Questions on the model parameters should be directed to the 
authors.

Questions on how to use this model with NEURON
should be directed to michele@pa.ibf.cnr.it
