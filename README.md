# Iterative Algorithms based on projections

## Laser Beam Fraunhofer Shaper - CPU Execution (`laserBeamShaping.ipynb`)

Iterative projection algorithm to shape the far-field intensity of a laser into a specified profile. CPU execution. The algorithm uses:

- **Far-field masks**: upper & lower amplitude bounds defining the desired main lobe and sidelobe levels in dB.
- **Aperture support**: binary mask for physical device support enforcement.

## Laser Beam Fraunhofer Shaper - GPU Execution (`laserBeamShapingCuPy.ipynb`)

Same as `laserBeamShaping.ipynb`, but now the execution in on GPU and is performed using the CuPy library.
