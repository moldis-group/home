## Quantum Mechanics 1, PHY-106.7/CHM-104.7

Course outline: [2021_QM1.pdf](teaching/2021_QM1.pdf)

#### _Syllabus:_ 

1. Fundamental concepts: Stern-Gerlach experiment; State vectors and operators; Bra-Ket notation: Hilbert space, Inner products; Matrix representation: Eigenkets, Spin-1/2 system, Measurements: Observables, Compatible/Incompatible observables, Uncertainty relations; Change of basis: Transformation, Continuous representation: Position/Momentum representation, Dirac delta function, Gaussian Wavepackets

2. Quantum dynamics: Time evolution and Schroedinger equation: Energy eigenkets, Stationary/nonstattionary states, Spin precession; Schroedinger/Heisenberg picture: Ehrenfest theorem, Transition amplitude; Simple harmonic oscillator: Stationary states, Time-evolution; Wave mechanics: Probability density, Classical limit; Elementary solutions to Schroedinger wave equation: Free particles, Infinitesquare well, Finite-square well, Transmission-Reflection problems Simple harmonic oscillator, Linear potential   

3. Theory of angular momentum: Rotations: Finite/infinite rotations, Commutation; Spin-1/2 system; Pauli 2-component quantum mechanics; Continuous groups: SO(3), SU(3), Euler rotations; Density operators: Pure-vs-mixed ensembles, time-evolution of ensembles, Quantum statistical mechanics; Eigenvalues and eigenstates of angular momentum; Orbital angular momentum: Spherical harmonics; Central potential problems, Hydrogen atom; Angular momentum algebra: Angular momentum
addition,Clebsh-Gordon coefficients; Oscillator model of angular momentum; Spin correlation measurements; Tensor operators: Wigner-Eckart theorem     

4. Approximation methods: Time-independent perturbation theory; Time-dependent perturbation theory; Application of perturbation theory to higher-order effects in Hydrogen atom Degenerate and nondegenerate versions; Variational method; WKB method   

#### _References:_     
Modern Quantum Mechanics, J. J. Sakurai, J. J. Napolitano, Pearson (Edition-2, 2011, Indian subcontinent reprint 2014).      

#### _Notes:_    
1. Detailed solution for the particle-in-a-1D-box using series solution method ([QM2021_Notes01_PIB.pdf](teaching/QM2021_Notes01_PIB.pdf))    

#### _Assignment problems:_     
[Assignment 01 (PDF)](teaching/QM2021_Assignment_01.pdf)     
[Assignment 02 (PDF)](teaching/QM2021_Assignment_02.pdf)     
[Assignment 03 (PDF)](teaching/QM2021_Assignment_03.pdf)    

#### _Exam problems:_    
[Mid-term (PDF)](teaching/QM2021_MidTerm.pdf)      

#### _Additional reading:_   
[Ten theorems about quantum mechanical measurements](https://doi.org/10.1016/0378-4371(88)90105-7) by N.G. Van Kampen, Physica A: Statistical Mechanics and its Applications, Elsevier (1988).      

* * *

## Numerical Methods, PHY-102.7/CHM-116.7

Course outline: [2021_NM.pdf](teaching/2021_NM.pdf)

#### _Syllabus:_      

1. Python: Writing/running codes, Jupyter notebooks, modules

2. Linear Equations: Direct methods: Cramer's rule, row-reduction, forward/backward substitution, Gaussian elimination; LU factorization: Cholesky's method

3. Data Modeling: Approximations: least squares fitting; Interpolation: polynomial interpolation, `scipy.interpolate.interp1d`

4. Root finding: The problem, fixed-point iteration, bisection method, Newton-Raphson method (1-D and n-D), Jacobian matrix, pseudo-inverse, quasi-Newton method (1-D: secant method, n-D: Broyden), `scipy.optimize` 

5. Optimization/Minimization: 1-D problems, n-D problems, `scipy.optimize.minimize(method=’L-BFGS-B’)`, Simplex method, `scipy.optimize.minimize(method=’Nelder-Mead’)`, How to select an optimization method?

6. Numerical Differentiation: Finite difference; Error analysis

7. Numerical Integration: Newton-Cotes formulae, Romberg/Gaussian integration, Multiple integrals

8. Initial Value Problems: Euler/Runge-Kutta methods; Stability and Stiffness

9. Boundary Value Problems: Shooting Method

10. Symmetric Matrix Eigenvalue Problems: Jacobi rotations, Power/inverse power method, Tridiagonal form

11. Application to Chemical Physics: Molecular thermodynamics (Ideal gas, harmonic oscillator, rigid rotor partition functions), Equation of states, Schroedinger equation of Hydrogen molecule cation, Hartree-Fock for He atom, Linear variational problems in Quantum mechanics (1D potentials, Tunneling problems), Potential energy surface fitting, Time-dependent Schroedinger equation. 

12. Optional Topics: Krylov Subspace Techniques, Lanczos iteration, Iterative linear solvers, Non-linear regression, Matrices: Rank and condition numbers

#### _Course material:_ 

Source files at [https://github.com/raghurama123/nm2021](https://github.com/raghurama123/nm2021)     
Interactive notebooks at [https://mybinder.org/v2/gh/raghurama123/nm2021/HEAD](https://mybinder.org/v2/gh/raghurama123/nm2021/HEAD)

#### _References:_     
Numerical Methods in Engineering with Python 3, Jaan Kiusalaas, Cambridge University Press (2013).      
A Student’s Guide to Python for Physical Modeling, Jesse M. Kinder, Philip Nelson, Princeton University Press (2018).       
Numerical Methods, W. Boehm, H. Prautzsch, Universities Press, 2000.       

#### _Additional reading:_    
[Introduction to object-oriented programming in Python with examples](https://www.programiz.com/python-programming/object-oriented-programming)     
[Square Roots from 1; 24, 51, 10 to Dan Shanks](https://www.maa.org/programs/maa-awards/writing-awards/square-roots-from-1-24-51-10-to-dan-shanks)      
[Babylon and the square root of 2](https://johncarlosbaez.wordpress.com/2011/12/02/babylon-and-the-square-root-of-2/)      
[PEP 8 — Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)   
[What Every Computer Scientist Should Know About Floating-Point Arithmetic](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)    

* * *
