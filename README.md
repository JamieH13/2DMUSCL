# 2D Riemann Solver

This fluid dyamics simulation uses a *Monotonic Upstream-centered Scheme for Conservation Laws* (MUSCL) scheme to simulation a simple Sod gas tube. This 
implementation uses a piecewise parabolic reconstruction higher-order extension of the Kurganov and Tadmor central scheme, with a Van-Albada flux limiter, which 
allows the simulation to remain stable in the case of large shock and discontinuities.

