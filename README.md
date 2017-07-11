# kinase_metadynamics
Set of sequence agnostic tICs capable of sampling the Chelix and 
DFG transitions in Tyrosine kinases. tICs optimized using ~1.5ms of
BTK trajectories. 

The feature space is the closest-heavy atom distances between 
conserved residues.We are using a sparse version of tICA which only
keeps ~5-20% of the total features in determining the coordinate. 
