
Strong stability preserving methods (also known as total variation diminishing, contractivity preserving, or monotonicity preserving methods), are numerical methods for solving ordinary differential equations. 

They were developed for the time integration of semi-discretizations of hyperbolic conservation laws. The exact solutions of scalar conservation laws have the property that their total variation does not increase in time. Semi-discretizations are often designed so that their discrete solutions also have this property under forward Euler integration. SSP methods are higher order methods that also preserve this property. Because of this, they were originally referred to as TVD methods. However, they have the stronger property that they will preserve any convex functional bound (such as, e.g., positivity) that is satisfied under forward Euler integration. 

This page shows the implementation (bitstream) of the ODE solvers on FPGAs using OpenCL.


