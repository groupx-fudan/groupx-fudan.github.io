# Micromagnetic Module on COMSOL Multiphysics

Micromagnetic simulation is an important numerical methods in studying magnetization or spin wave dynamics. The essential task is to solve the non-linear semi-classical Landau-Lifshitz-Gilbert equation in various geometries and magnetic texture configurations. There are several excellent micromagnetic simulation packages, such as OOMMF, MuMax3, … Most of these packages use the finite difference method (FDM), which discretize the geometry into regular cubiod mesh. A more efficient spatial discretization method is the finite element method (FEM). 

We developed the Micromagnetics Module, a new micromagnetic simulation package based on the COMSOL platform, which provides an excellent finite element analysis and model designing tools. The Micromagnetics Module built upon COMSOL can be integrated straightforwardly with other physical modules within COMSOL such as the Solid Mechanics Module  (for magneto-elastic coupling) and AC/DC or RF Module (for electromagnetics, cavity spintronics).

The Micromagnetics Module is mainly developed and maintained by Dr. Weichao Yu, started from his PhD study under supervision of [Prof. Jiang Xiao](../members/jiangxiao.md). For more information, please visit the [COMSOL blog](https://www.comsol.com/blogs/micromagnetic-simulation-with-comsol-multiphysics/) 
([中文版](https://cn.comsol.com/blogs/micromagnetic-simulation-with-comsol-multiphysics/)).

## Features

The features of the Micromagnetics Module (V1.33) include but not limited to:

- Basic Landau–Lifshitz–Gilbert formalism, including exchange interactions and uniaxial anisotropy

- Dzyaloshinskii–Moriya interaction (both bulk and interfacial types) with appropriate boundary conditions

- Spin-transfer torque with both damping- and field-like terms

- Arbitrary field and torque input (time- and space dependent)

- Finite temperature effect (with arbitrary random seed)

- Pinning boundary conditions and periodic boundary conditions

- Capability of solving multiple independent LLG equations in one region (such as synthetic antiferromagnets with multiple sublattices)

- Capability of multiphysics coupling, including magneto-dipolar coupling, magneto-elastic coupling, magneto-electric coupling, and magneto-thermal coupling

## Requirements

To install the Micromagnetics Module, a basic version of COMSOL Multiphysics® software is required. To perform Multiphysics micromagnetic simulations, further add-on modules are needed such as Solid Mechanics Module for magneto-elasitc simulations and AC/DC Module for magneto-dipolar simulations.

## Resources

1. The module file along with the 
[User’s Guide](http://www.physics.fudan.edu.cn/tps/people/jxiao/micromagnetics-module-users.pdf) 
can be downloaded 
[here](https://www.jianguoyun.com/p/Dbm-n-QQqfTwCRjHpZAE) 
with access password 'fudan'. 

2. Module file and the User’s Guide can also be downloaded at the COMSOL Application Exchange [website](https://cn.comsol.com/community/exchange/883/).

3. Files will also be updated at the project homepage of Dr. Weichao Yu on [ResearchGate](https://www.researchgate.net/project/Micromagnetics-Module). 
Users are encouraged to leave comments and questions there to help us improve the module.

## References

Here is a partial list of the papers that we published using the Micromagnetics Module. We would appreciate if you could cite one or more of the following papers if you use the module in your own research.

1. Yu, W., Xiao, J. & Bauer, G. E. W. A Hopfield neural network in magnetic films with natural learning. arXiv:2101.03016 (2021).

2. Yu, W., Lan, J. & Xiao, J. Magnetic Logic Gate Based on Polarized Spin Waves. Phys. Rev. Applied 13, 024055 (2020).

3. Yu, W., Wang, J., Yuan, H. Y. & Xiao, J. Prediction of Attractive Level Crossing via a Dissipative Mode. Phys. Rev. Lett. 123, 227201 (2019).

4. Yu, W., Lan, J. & Xiao, J. Polarization-selective spin wave driven domain-wall motion in antiferromagnets. Phys. Rev. B 98, 144422 (2018).

5. Lan, J., Yu, W. & Xiao, J. Antiferromagnetic domain wall as spin wave polarizer and retarder. Nature Communications 8, 178 (2017).

6. Yu, W., Lan, J., Wu, R. & Xiao, J. Magnetic Snell’s law and spin-wave fiber with Dzyaloshinskii-Moriya interaction. Phys. Rev. B 94, 140410 (2016).

7. Lan, J., Yu, W., Wu, R. & Xiao, J. Spin-Wave Diode. Phys. Rev. X 5, 041049 (2015).