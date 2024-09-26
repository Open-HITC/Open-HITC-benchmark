# Open HITC benchmark


## Objectives

Many [numerical codes](CODES.md) are developped to study hydrogen transport in materials. 

A series of test cases are provided by developers for [verification and validation](EXAMPLES.md). 

Open HITC (hydrogen isotope transport code) benchmark is designed to list test cases applied in order to cross-check the results of different codes. 
Authors of published test cases can upload (or link to) their raw results and/or scripts with parameters to facilitate benchmarking: this avoids having to search the papers for every parameter (sometimes included in other papers) and digitise the curves yourself.

The reproduction of applied examples of reference codes by several codes also shows that many codes could be used for qualification.

## Applied cases

The purpose of the applied test cases is to verify the operational functions of the codes, grouped by category (capital letter) and sub-category by increasing complexity (number). 

- A. TDS reproduction 
    - A.1. Simple TDS reproduction (minimum first guess)
- B. Diffusion
    - B.1. [Multimaterial diffusion](IB1/README.md)
    - B.2. Multispecies diffusion
    - B.3. [Soret effect in W](IB3/README.md)
- C. Boundary condition
    - C.1. Sievert BC
    - C.2. Neumann BC
    - C.3. Implantation source term
    - C.4. Kinetic surface model
- D. Trap mechanisms
    - D.1. Non-uniform spatial distribution
    - D.2. Trap creation with time
    - D.3. Discrete mutli-occupancy traps
- E. Multidimensionnal
    - E.1. 2D Divertor Monoblock cases
    - E.2. 3D Divertor Monoblock cases
- F. General
    - F.1. Unlimited traps
    - F.2. Unlimited traps
    - F.3. Code accessibility


See also: 
- [CODES.md](CODES.md) List of some existing codes
- [EXAMPLES.md](EXAMPLES.md) List of some verification and validation of existing codes

*The project began as part of the ITER Science Fellow "Fuel retention" led by Tom Wauters.*
