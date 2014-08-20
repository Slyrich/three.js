three.js
========
Simulation of Microtubules

Microtubules are long, hollow tubes which are arranged from a large number of aligned tubulin dimers. The actual details of this self-assembly are not entirely clear. Also, the process by which microtubules break down is not known.Tubulins and the dimmers resulting from them are the building blocks of the microtubule formation. Alpha tubulin can be attached to beta tubulin only at specific binding sites and this information is stored in the respective tubulins.

In our approach, we are trying to use THREE.js to establish a computational simulation system with a set of selective parameters, and find the most efficient way of microtubules Self-assembly.

Behavior rules for computer simulation:

1. A dimer is built from alpha and beta tubulins.
2. All dimmers are free to move with purely Brownian motion.
3. Free dimers can randomly rotate to achieve a specific orientation.
4. All dimers have "stickness" factors through Guanosine triphosphate molecules(GTP) so that alpha and beta tubulins can attract either axially or laterally or unbound.
5. Once microtubules starts forming, it stops moving.
6. Dimers have specific binding sites where the adjacent dimers can attach to form crosslinks.
7. The number of possible binding sites available for a newly accreting dimer is dependent upon the size of the protofilament.
8. The information for generating the protofilament shape is contained in the dimers itself.


http://3.bp.blogspot.com/_guSOnFRs_Ks/TJySPEDW9eI/AAAAAAAAAOU/0SbkWQznxqk/s1600/microtubule.gif
