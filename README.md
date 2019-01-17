# PyRosetta_Project
#Ran single site mutagenesis flex ddG - like project. 

1 start
clean pdbs -
fastrelax WT pose- (relax-constraints-to-start coords)
create ensemble - backrub

2A
FastRelax-
    - can lower repeats to two
    - consider 2 shells
Global minimization
WT Score -

2B
Mutate - residue selector, task factory
FastRelax-
    - can lower repeats to two
    - consider 2 shells
Score mutant
 
PDB- 3m1i A
 



