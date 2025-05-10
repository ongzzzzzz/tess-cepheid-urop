# Spring 2025 UROP Writeup

Goal: Use [TESS data](https://archive.stsci.edu/missions-and-data/tess) to calculate the Hubble constant using cepheids.

Catalogs used: OGLE, Gaia DR3, TESS

Search for catalogs on https://vizier.unistra.fr/

TESS data can be downloaded using `lightkurve`

In the Python code, the following are done:
- Visualizing Gaia Cepheid Dataset distributions
- Crossmatching Gaia Cepheids to TESS IDs (in progress)
- Recreating Light curves from the main paper
- Looking into the LMC/SMC (in progress)

## References

Main paper: [TESS Observations of Cepheid Stars: First Light Results](https://iopscience.iop.org/article/10.3847/1538-4365/abd4e3)

### Hubble Papers

- [Status Report on the Chicago-Carnegie Hubble Program (CCHP): Measurement of the Hubble Constant Using the Hubble and James Webb Space Telescopes](https://arxiv.org/abs/2408.06153)
- [Measurements of the Hubble Constant: Tensions in Perspective](https://arxiv.org/abs/2106.15656)
- [Towards a 1% measurement of the Hubble constant: accounting for time dilation in variable-star light curves](https://www.aanda.org/articles/aa/abs/2019/11/aa36585-19)
- [The Near-infrared Optimal Distances Method Applied to Galactic Classical Cepheids Tightly Constrains Mid-infrared Period–Luminosity Relations](https://iopscience.iop.org/article/10.3847/1538-4357/aa9d99)
- [Astrophysical Distance Scale The JAGB Method: I. Calibration and a First Application](https://arxiv.org/abs/2005.10792)
- [(Caltech) A reddening-free formulation of the PL relation](https://ned.ipac.caltech.edu/level5/Cepheids/Cepheids14.html)
- [A Comprehensive Measurement of the Local Value of the Hubble Constant with 1 km s−1 Mpc−1 Uncertainty from the Hubble Space Telescope and the SH0ES Team](https://iopscience.iop.org/article/10.3847/2041-8213/ac5c5b)
  - Uses a few ways to get to H
- [Large Magellanic Cloud Cepheid Standards Provide a 1% Foundation for the Determination of the Hubble Constant and Stronger Evidence for Physics beyond ΛCDM](https://iopscience.iop.org/article/10.3847/1538-4357/ab1422)
  - Review of methods to get distances


### Cepheid Papers

- [The Milky Way as seen by Classical Cepheids I: distances based on mid-infrared photometry](https://arxiv.org/abs/2406.09113)
    - [The Near-infrared Optimal Distances Method Applied to Galactic Classical Cepheids Tightly Constrains Mid-infrared Period–Luminosity Relations](https://iopscience.iop.org/article/10.3847/1538-4357/aa9d99)
- [Variable stars in Galactic globular clusters II. Population II Cepheids](https://arxiv.org/abs/2502.18158)
- [Classification of Periodic Variable Stars from TESS](https://arxiv.org/abs/2412.06175)
- [Cluster Cepheids with High Precision Gaia Parallaxes, Low Zeropoint Uncertainties, and Hubble Space Telescope Photometry](https://arxiv.org/pdf/2208.01045)
