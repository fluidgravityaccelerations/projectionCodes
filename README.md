# Iterative Algorithms based on projections

See D.R. Prado, "The generalized intersection approach for electromagnetic array antenna beam-shaping synthesis: a review," IEEE Access, vol. 10, pp. 87053-87068, 2022

## Laser Beam Fraunhofer Shaper based on an Iterative Projection Algorithm - CPU Execution (`laserBeamShaping.ipynb`)

Iterative projection algorithm to shape the far-field intensity of a laser into a specified profile. CPU execution. The algorithm uses:

- **Far-field masks**: upper & lower amplitude bounds defining the desired main lobe and sidelobe levels in dB.
- **Aperture support**: binary mask for physical device support enforcement.

## Laser Beam Fraunhofer Shaper based on an Iterative Projection Algorithm - GPU Execution (`laserBeamShapingCuPy.ipynb`)

Same as `laserBeamShaping.ipynb`, but now the execution in on GPU and is performed using the CuPy library.

## Laser Beam Fraunhofer Shaper based on a Generalized Projection Algorithm - CPU Execution (`laserBeamShapingGeneralized.ipynb`)

Generalized projection algorithm to shape the far-field intensity of a laser into a specified profile. CPU execution. The algorithm uses:

- **Far-field masks**: upper & lower amplitude bounds defining the desired main lobe and sidelobe levels in dB.
- **Optimization algorithm**: to determine the aperture field from the constrained far-field.
