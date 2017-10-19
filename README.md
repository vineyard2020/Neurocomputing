# Neurocomputing
Neurocomputing Applications


## Inferior-Olive Nucleus Brain modelling

The first application targets the acceleration of the modeling application that simulates the Inferior-Olive Nucleus (ION). The application, depending on the scale of the simulated network, it may require low latency, high throughput or both. Since within the VINEYARD project the application is targeting large networks, the critical requirement is high throughput, thus the Maxeler DFE platform is a great match for such a requirement. Mostly since the ION application is largely a dataflow application and has good acceleration potential on the specific accelerator platform. 

## Ordinary Differential Equations

Another widely used algorithm for neurocomputing applications is the algorithm that is based on Ordinary Differential Equations. ODEs are widely used in many high-performance computing applications in neurocomputing applications. However, contemporary processors generally provide limited throughput for these kinds of calculations. A high-performance hardware accelerator has been developed for speeding-up the solution of ODEs. The hardware accelerator has been developed both for single and double floating-point precision types and a design-space exploration has been performed in terms of performance and hardware resources. The hardware accelerator has been mapped to an FPGA board and connected through PCIe to a typical processor. The performance evaluation shows that the proposed scheme can achieve up to 14x speedup compared to a reference, single-core CPU solution. 

This application requires tight communication between the processor and the exelerator thus the accelerators have been developed for the PCI-based FPGA accelerator based on Alpha Data KU3 FPGA card.



