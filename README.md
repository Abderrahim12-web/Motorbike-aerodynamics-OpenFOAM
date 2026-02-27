This project investigates the external aerodynamics of a sport motorbike with rider using OpenFOAM.
The geometry was prepared and discretized using snappyHexMesh, and the steady turbulent flow was simulated with the simpleFoam solver.
The objective was to analyze the aerodynamic behavior of the motorbike under different flow conditions by computing and monitoring key aerodynamic quantities.

KEY TASKS PERFORMED:

Generated a body-fitted mesh around the motorbike.
Simulated steady incompressible turbulent flow.
Computed aerodynamic forces on the vehicle.
Plotted force coefficients over time.

MAIN OUTPUT ANALYZED:

1. Drag coefficient (Cd): resistance to motion.

2. Lift coefficient (Cl): vertical aerodynamic force.

3. Wake structure behind the motorbike.

4. Flow separation and turbulence effects.

AIM OF THE STUDY:

To understand how the motorbike’s aerodynamic performance changes with operating conditions and to evaluate its stability and efficiency using force-coefficient analysis.

SOLVERS AND TOOLS USED:

blockMesh — create background computational domain.

snappyHexMesh — generate body-fitted mesh around the motorbike.

simpleFoam — steady-state incompressible turbulent flow solver.

decomposePar / reconstructPar — parallel processing.

ParaView — post-processing and visualization.

forceCoeffs function — computation of aerodynamic coefficients.
