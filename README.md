# Iterative Algorithms based on projections

## Laser Beam Fraunhofer Shaper - No Aperture Field Symmetry Enforced (`laserBeamShapingUnsymmetrical.ipynb`)

Iterative projection algorithm to shape the far-field intensity of a laser into a specified profile. No symmetry of the aperture field is enforced. The far-field phase turns out to be tilted. The algorithm uses:

- **Far-field masks**: upper & lower amplitude bounds defining the desired main lobe and sidelobe levels in dB.
- **Aperture support**: binary mask for physical device pixels/phases.

