Brief overview:

The sample code I've adapted from CoQ code for the folP branch point. 

Key points:
- lammps-branch-trial.in: new .in file adapted for that specific scenario
- new_system.data from the edited generate_system_data.py, adapted from original posted in CoQ
- Since I implement fix bond/react, I have corresponding .txt and .map files

.txt and .map files:
- folP:DHPP + PABA reaction -> folP + product + Ppi crowder (preTriad.txt, postTriad.txt, triad.map)
- folP + DHPP -> folP:DHPP -> folP + DHPP (reversible) (preComp1.txt, postComp1.txt, comp1.map)

There are many pictures (png files) for my trying to experiment with image dumps. They have not been successful/great so feel free to ignore them.
