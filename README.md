# Open HITC benchmark

Open HITC (hydrogen isotope transport code) benchmark is a qualification tool for hydrogen transport codes. A series of test cases are provided to allow for verification and validation.

We distinguish three types of verification tests: those applied to fusion problems (I), those with an analytical solution (II) and manufactured solutions (III).

## I. Applied tests
The purpose of the applied test cases is to verify the operational functions of the codes, grouped by category (capital letter) and sub-category by increasing complexity (number). 

- A. TDS reproduction 
    - A.1. Simple TDS reproduction (minimum first guess)
- B. Diffusion
    - B.1. [Multimaterial diffusion](IB1/README.md)
    - B.2. Multispecies diffusion
    - B.3. Soret effect
- C. Boundary condition
    - C.1. Sievert BC
    - C.2. Neumann BC
    - C.3. Implantation source term
    - C.4. Kinetic surface model
- D. Trap mechanisms
    - D.1. Non-uniform spatial distribution
    - D.2. Trap creation with time
    - D.3. Discrete multi-energetic traps
- E. Multidimensionnal
    - E.1. 2D cases
    - E.2. 3D cases
- F. General
    - F.1. Unlimited traps
    - F.2. Unlimited traps
    - F.3. Code accessibility

## II. Analytical tests

(Tbd)

## III. Manufactured solutions tests

(Tbd)


## Contribution synthesis

<br>

See also: 
- [CODES.md](CODES.md) List of some existing codes
- [EXAMPLES.md](EXAMPLES.md) List of some verification and validation of existing codes

*The project began as part of the ITER Science Fellow "Fuel retention" led by Tom Wauters.*
