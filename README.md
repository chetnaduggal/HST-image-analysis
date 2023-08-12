# A Hubble view of Compact Steep-Spectrum (CSS) host galaxies

Reduction and mapping of HST/WFC3 optical/UV continuum data for a sample of compact, young radio galaxies (Cycle 25 GO program 15245; PI: C. O’Dea). 7 of these are CSS galaxies hosting kpc-scale steep-spectrum radio source.

The codes include:

- Post-pipeline processing of HST images with the [Drizzlepac](https://www.stsci.edu/scientific-community/software/drizzlepac.html) software.
- Mapping continuum emission in the three bands (optical, UV and radio) by reprojecting the images onto a new, optimum WCS grid to create multi-wavelength overlays.
- The results of surface brightness analysis with [IRAF/ellipse](http://stsdas.stsci.edu/documents/SUG/UG_33.html) isophote fitting & 2D morphological decomposition with [GALFIT](https://users.obs.carnegiescience.edu/peng/work/galfit/galfit.html). The galaxy fit profiles for the latter are generated using the [Ellipsect](http://github.com/canorve/EllipSect) code.
- Comparison of major-axis Position Angles of the observed galaxy/radio-source structure in the optical, near-UV and radio bands.
- Galactic and internal extinction corrections using E(B−V) color excess sourced from the [NASA/IPAC](https://irsa.ipac.caltech.edu/applications/DUST/) archive. 
- Plotting photometric spectral energy ditributions (SEDs) for the 9 compact radio galaxies.

All the scripts in this repository are associated with a new study of AGN feedback in CSS host galaxies, recently submitted to ApJ.

------
