# NACA 2412 Bird Strike Simulation

I used ANSYS Mechanical Explicit Dynamics to simulate a bird striking the
leading edge of a simplified NACA 2412 wing shell at 213.66 m/s. The bird
was represented using smoothed particle hydrodynamics (SPH).

At the final saved frame (3.0004 ms), the maximum wing displacement was
14.943 mm. The report compares this elastic simulation qualitatively with
Case II from Walvekar et al. (2010) and explains the differences in the
impact setup and structural model.

- [Comparison report](report/Bird_Strike_Comparison_Report.pdf)
- [Geometry files](geometry/)
- [Simulation images and video](media/)

The model captures transient elastic response and particle dispersion.
Experimental validation of structural damage remains open.
