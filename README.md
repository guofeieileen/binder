#Identifying Protein-Protein Interface via a Novel Multi-Scale Local Sequence and Structural Representation

We obtain the local information on protein-protein interface, through multi-scale local average block and hexagon structure construction. 
Given a pair of proteins, we use a trained support vector regression (SVR) model to select best configurations. 

We test the 176 complexes in Benchmark v4.0. The results are here. The files contain the best ten prediction configurations (such as 1A0O-1s.pdb, 1A0O-2s.pdb) with the lowest energy value.

To obtain statistical properties of the new properties across the protein-protein interface, we adopt a high quality, non-redundant experimental data set. We select 6,438 complexes from Protein Data Bank (PDB) database, and each complex consists of two or more protein subunits. These complexes are determined from X-ray data with resolution no more than 2.2 Angstrom. Any two complexes share no more than 30 percent identity to avoid biases in the database.
