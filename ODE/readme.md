# ODE Solvers

Ordinary Differential Equations (ODEs) are widely used in many high-performance computing applications. However, contemporary processors have limited throughput in these kinds of calculations. A high-performance hardware accelerator has been developed for speeding-up the solution of ODEs. The hardware accelerator has been developed both for single and double floating-point precision types and a design-space exploration has been performed in terms of performance and hardware resources. The hardware accelerator has been mapped to an FPGA board and connected through PCIe to a typical processor. The performance evaluation shows that the proposed scheme can achieve up to 12x speedup compared to a reference single core CPU solution.

For the numerical solution of the above model problem we adopt four widely-used ODE solvers, namely:
* Forward Euler (FwdEuler), 
* Modified Euler (ModEuler), 
* and strong stability preserving Runge-Kutta schemes of:
** order two (SSP-RK2) and
** three (SSP-RK3). 

All four methods are fully explicit and thus, lend themselves to parallel implementations. The computational complexity increases from the single-step forward Euler method to the two- and three-step Runge-Kutta methods, so that the speedup of the FPGA implementation over the software solution is expected to be highest for FwdEuler but still considerable for ModEuler, SSP-RK2 and SSP-RK3. The benefit of the latter is, however, their higher temporal accuracy. Furthermore, the selected ODE solvers are used as time-integrators for partial differential equations (PDEs), especially hyperbolic conservation laws, and therefore, the development of efficient FPGA-accelerated solution procedures has the potential to significantly speed-up the numerical simulations of PDE problems at a later stage.

For more information: www.vineyardh2020.eu

