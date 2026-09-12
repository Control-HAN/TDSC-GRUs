# TDSC-GRU
S. Y. Han, “Timer-Dependent Synchronization of Mismatched Gated Recurrent Units under Random Replay Attack,” International Journal of Systems Science (Under Review).



----

MATLAB implementation of **Timer-Dependent Synchronization Controller for GRUs (TDSC-GRUs) ** by [Seungyong Han](https://sites.google.com/view/jbnu-dscl)

<!-- <p align="center">
  <img src="Figures/03_Ex1_Case1_Leader_Follower_Trajectory.png" width="250" />
  <img src="Figures/12_Ex2_Case1_NODE_MPC_ILMPC_State.png" width="250" />
  <img src="Figures/19_Ex2_Case2_NODE_MPC_TDMPC_State.png" width="250" />
</p> -->

# 1. Method

The timer-dependent synchronization controller (TDSC) design is proposed for master-slave synchronization of mismatched gated recurrent units (GRUs) under replay attacks. The slave GRU is subject to both structural mismatches and replayed network information, which can degrade synchronization performance. The proposed TDSC employs a timer-dependent controller to account for the elapsed time between sampling instants. A hybrid Lyapunov functional incorporating the timer variable and the maximum delay index of replayed samples is introduced to derive sufficient synchronization conditions. The controller is designed with an $H_{\infty}$ performance criterion to reduce the influence of structural mismatches on the synchronization error. The resulting controller design conditions are formulated using sum-of-squares (SOS) programming. Numerical simulations demonstrate that the proposed method improves synchronization performance under random replay attacks and model mismatches.


# 2. Requirements
- MATLAB R2024b+
- YALMIP (available at https://yalmip.github.io/download/)
- SOSTOOLS (available at https://www.cds.caltech.edu/sostools/)
- MOSEK (available at https://www.mosek.com/downloads/)
  
## Contact
 - If you have questions or suggestions, please reach out via email [hansy@jbnu.ac.kr](mailto:hansy@jbnu.ac.kr).
