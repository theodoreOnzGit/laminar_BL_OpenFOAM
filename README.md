# laminar_BL_OpenFOAM
This is a laminar boundary layer using OpenFOAM's icoFoam solver.

The boundary conditions in the U file are...

we have zeroGradient on the top and bottom of the entrance region.
we have constant velocity on left side of entrance region.
we have zeroGradient on top of the flat plate region and the right hand side. 
we have noSlip condition on bottom of flat plate region.
