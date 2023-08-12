# A Hubble view of Compact Steep-Spectrum (CSS) host galaxies

Reduction and mapping of HST/WFC3 optical/UV continuum data for a sample of compact, young radio galaxies (Cycle 25 GO program 15245; PI: C. O’Dea).

The codes show the results of:

- Drizzle and tweakreg
- Mapping continuum emission in the three bands (optical, UV and radio) by reprojecting the images onto a new, optimum WCS grid to create multi-wavelength overlays.
- Surface brightness analysis with [IRAF/ellipse](http://stsdas.stsci.edu/documents/SUG/UG_33.html) isophote fitting & 2D morphological decomposition with [GALFIT](https://users.obs.carnegiescience.edu/peng/work/galfit/galfit.html). The galaxy fit profiles for the latter are generated using the [Ellipsect](http://github.com/canorve/EllipSect) code.
- Comparison of major-axis Position Angles of the observed galaxy/radio-source structure in the optical, near-UV and radio bands.
- Photometric exntiction correction
- Plotting photometric spectral energy ditributions (SEDs) for the 9 radio galaxies

All the scripts in this repository are associated with a new study recently submitted to ApJ.

------
