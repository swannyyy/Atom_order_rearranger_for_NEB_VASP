# Atom_order_rearranger_for_NEB_VASP
You know when you need to rearrange the order of the atoms in the initial geometry because it is different in the final one and you cannot interpolate the images for the NEB. This code does it for you. It kinda works 98% of the times, worst case is you need to swap manually a couple of atoms 
The code takes as input the initial and final geometry and rearranges the first one. It creates a mapping of the atoms and iteratively tries to replicate the mapping of the final geometry in the initial one. 
