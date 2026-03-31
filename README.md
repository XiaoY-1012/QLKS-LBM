# QLKS-LBM
Supplementary code for the publication: Xiao Yang, Yang Liming, Shu Chang, Du Yinjie, Dong Hao, Wu Jie. Quantum Lattice Kinetic Scheme for Solving Two-dimensional and Three-dimensional Incompressible Flows. arXiv preprint arXiv:2505.10883. This code is an expansion based on the work of "Wawrzyniak D, Winter J, Schmidt S, Indinger T, Janßen CF, Schramm U, Adams NA. A quantum algorithm for the lattice-Boltzmann method advection-diffusion equation. Computer Physics Communications. 2025, 306:109373".
# Abstract
Lattice Boltzmann method (LBM) is particularly well-suited for implementation on quantum circuits owing to its simple algebraic operations and natural parallelism. However, most quantum LBMs fix τ = 1 to simplify the lattice Boltzmann equation to a linear system with respect to the equilibrium distribution function, which restricts the simulation to a fixed mesh size for a given Reynolds number. To preserve the simplicity of setting τ = 1 while enhancing flexibility, we propose a quantum lattice kinetic scheme (LKS) by introducing a constant parameter A into the equilibrium distribution function (EDF), enabling independent adjustment of the fluid’s viscosity. This modification removes the constraint on mesh size, making it possible to simulate flows with arbitrary Reynolds numbers. The Chapman-Enskog analysis confirms that the modified EDF still recovers the Navier-Stokes equations without compromising accuracy. We evaluate the method on 2D and 3D Taylor-Green vortex and lid-driven cavity flows, demonstrating that quantum LKS attains the same accuracy and convergence order as classical LKS. The first application of quantum LBM to 3D incompressible flows represents a significant step forward in large-scale fluid dynamics simulation.
# Citation
@article{xiao2025quantum,<br>
  title={Quantum Lattice Kinetic Scheme for Solving Two-dimensional and Three-dimensional Incompressible Flows},<br>
  author={Xiao, Yang and Yang, Liming and Shu, Chang and Du, Yinjie and Dong, Hao and Wu, Jie},<br>
  journal={arXiv preprint arXiv:2505.10883},<br>
  year={2025}<br>
}
