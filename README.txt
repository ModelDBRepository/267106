////////////////////////////////////////////////////////////////////////////////
//
// Code by Jan M Schulz and Josef Bischofberger, University of Basel, 2019-20.
// Correspondence can be addressed to j.schulz@unibas.ch
// 
// Computational models of young and mature granule cells in
// Lodge, Hernandez, Schulz, and Bischofberger, Cell Reports, 2021.
//
// The enclosed code distributes glutamertic and GABAergic synapses over the dendritic tree 
// of a stylized granule cell (either mature or young) and tests the effect of voltage-dependent
// versus linear inhibition on NMDA receptor-mediated depolarization and AP output depending on synapse numbers
//
// To load in the NEURON simulation environment:
// 1. Download and install NEURON (http://www.neuron.yale.edu/neuron/) if needed
// 2. Make sure that Python is installed and, in Windows, that the location of the installation (e.g. C:\Python27) is added 
//    to the System PATH variable (to be found in the Environment Variables under Advanced Settings of System Properties). 
// 3. Compile all .mod files of the simulation directory via mknrndll.
// 4. Modify start_simul.hoc to select one simulation from Fig.5 or 7.
// 5. Start the simulation by running start_simul.
//
////////////////////////////////////////////////////////////////////////////////