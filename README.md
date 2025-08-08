# Iterative Algorithms based on projections

## Laser Beam Fraunhofer Shaper - CPU Execution - No Aperture Field Symmetry Enforced (`laserBeamShapingUnsymmetrical.ipynb`)

Iterative projection algorithm to shape the far-field intensity of a laser into a specified profile. No symmetry of the aperture field is enforced. The far-field phase turns out to be tilted (local plane wave not propagating longitudinally). CPU execution. The algorithm uses:

- **Far-field masks**: upper & lower amplitude bounds defining the desired main lobe and sidelobe levels in dB.
- **Aperture support**: binary mask for physical device support enforcement.

## Laser Beam Fraunhofer Shaper - CPU Execution - Aperture Field Symmetry Enforced (`laserBeamShapingSymmetrical.ipynb`)

Same as before, but aperture field symmetry enforced. CPU execution. The far-field phase turns out to be flat (local plane wave propagating longitudinally).

## Laser Beam Fraunhofer Shaper - GPU Execution - No Aperture Field Symmetry Enforced (`laserBeamShapingUnsymmetricalCuPy.ipynb`)

Same as `laserBeamShapingUnsymmetrical.ipynb`, but now the execution in on GPU and is performed using the CuPy library.
