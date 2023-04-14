# Proof of Kariya's theorem with Groebner basis computation

This directory contains Risa/Asir programs and data for compting proofs of Kariya's theorem with Groebner basis computation.

## Theorem (kariya-theorem)

### Vertex formulation

#### Computing Groebner basis

- kariya-theorem-vertex-groebner-ideal.rr: computing Groebner basis for the proof
- kariya-theorem-vertex-groebner-ideal-timing.rr: a script for measuring running time for computing Groebner basis
    - log/kariya-theorem-vertex-groebner-ideal-timing.log: a timing data
- G_kariya_theorem_vertex_ideal.dat: the Groebner basis 

#### Computing a proof

- kariya-theorem-vertex-groebner-ideal-proof.rr: computing the normal form of polynomial g with respect to the Groebner basis
- kariya-theorem-vertex-groebner-ideal-proof-timing.rr: a script for measuring running time for computing the norm form of polynomial g with respect to the Groebner basis
    - log/kariya-theorem-vertex-groebner-ideal-proof-timing.log: a timing data

### Theorem with using ''r'' for the radius of the incircle

A formulation using ''r'' for the radius of the incircle. In the files in the previous section, ''x13'' is used instead.

- kariya-theorem-vertex-groebner-ideal-r.rr: computing Groebner basis for the proof
- G_kariya_theorem_vertex_ideal_r.dat: the Groebner basis 
- kariya-theorem-vertex-groebner-ideal-proof-r.rr: computing the normal form of G with respect to the Groebner basis

### Incenter formulation

#### Computing Groebner basis

- kariya-theorem-incenter-groebner-ideal.rr: computing Groebner basis for the proof
- kariya-theorem-incenter-groebner-ideal-timing.rr: a script for measuring running time for computing Groebner basis
    - log/kariya-theorem-incenter-groebner-ideal-timing.log: a timing data
- G_kariya_theorem_incenter_ideal.dat: the Groebner basis

#### Computing a proof

- kariya-theorem-incenter-groebner-ideal-proof.rr: computing the normal form of polynomial g with respect to the Groebner basis
- kariya-theorem-incenter-groebner-ideal-proof-timing.rr: a script for measuring running time for computing the norm form of polynomial g with respect to the Groebner basis
    - log/kariya-theorem-incenter-groebner-ideal-proof-timing.log: a timing data

## Corollary (kariya-corollary)

### Vertex formulation

#### Computing Groebner basis

- kariya-corollary-vertex-groebner-ideal.rr: computing Groebner basis for the proof
- kariya-corollary-vertex-groebner-ideal-timing.rr: a script for measuring running time for computing Groebner basis
    - log/kariya-corollary-vertex-groebner-ideal-timing.log: a timing data
- G_kariya_corollary_vertex_ideal.dat: the Groebner basis

#### Computing a proof

- kariya-corollary-vertex-groebner-ideal-proof.rr: computing the normal form of polynommial g with respect to the Groebner basis
- kariya-corollary-vertex-groebner-ideal-proof-timing.rr: a script for measuring running time for computing the norm form of polynomial g with respect to the Groebner basis
    - log/kariya-corollary-vertex-groebner-ideal-proof-timing.log: a timing data

### Incenter formulation

#### Ideal membership (failed to proof)

##### Computing Groebner basis
- kariya-corollary-incenter-groebner-ideal.rr: computing Groebner basis for the proof
- G_kariya_corollary_incenter_ideal.dat: the Groebner basis

##### Proof

- kariya-corollary-incenter-groebner-ideal-proof.rr: computing the normal form of polynomial g with respect to the Groebner basis (which is not equal to zero)

#### Radical membership

##### Computing Groebner basis
- kariya-corollary-incenter-groebner-radical.rr: computing Groebner basis for examining the radical membership 
- kariya-corollary-incenter-groebner-radical-timing.rr: a script for measuring running time for computing the Groebner basis for examining the radical membership
    - log/kariya-corollary-incenter-groebner-radical-timing.log: a timing data

## Fauerbach hyperbola proof (fauerbach)

### Vertex formulation

- feuerbach-vertex-groebner-proof.rr: computing the normal form of polynomial F with respect to the Groebner basis
- feuerbach-vertex-groebner-proof-timing.rr: a script for measuring running time for computing the norm form of polynomial F with respect to the Groebner basis
    - log/feuerbach-vertex-groebner-proof-timing.log: a timing data

### Incenter formulation

- feuerbach-incenter-groebner-proof.rr: computing the normal form of polynomial F with respect to the Groebner basis
- feuerbach-incenter-groebner-proof-timing.rr: a script for measuring running time for computing the norm form of polynomial F with respect to the Groebner basis
    - log/feuerbach-incenter-groebner-proof-timing.log: a timing data