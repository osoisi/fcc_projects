# fcc_projects
 Freecodecamp Data Science Projects

# Project 1: MAGIC Gamma Telescope Dataset - GitHub README

**Dataset Overview:**
- **Source:** UCI Machine Learning Repository
- **Donation Date:** April 30, 2007
- **Creator:** R. Bock
- **Simulation Tool:** Monte Carlo program (Corsika)
- **License:** CC BY 4.0 - Share and adapt with proper credit.

**Description:**
This dataset contains simulated data from the MAGIC (Major Atmospheric Gamma Imaging Cherenkov) telescope, aimed at distinguishing gamma rays from hadron showers. The data was generated using the Corsika Monte Carlo simulation.

**Features:**
- **fLength:** Major axis of ellipse (mm)
- **fWidth:** Minor axis of ellipse (mm)
- **fSize:** 10-log of total pixel content (#phot)
- **fConc:** Ratio of sum of top two pixels to fSize
- **fConc1:** Ratio of highest pixel to fSize
- **fAsym:** Distance from highest pixel to center along major axis
- **fM3Long:** 3rd root of third moment along major axis (mm)
- **fM3Trans:** 3rd root of third moment along minor axis (mm)
- **fAlpha:** Angle of major axis with vector to origin (deg)
- **fDist:** Distance from origin to ellipse center (mm)
- **class:** Binary classification (gamma/hadron)

**Objective:**
Using the provided features, classify telescope observations into gamma signals (the target) and hadron-induced showers (the background).

**Discrimination Factors:**
- Shape and orientation of the shower image
- Asymmetry along the major axis
- Cluster extent in the image plane
- Total energy deposition

This dataset is ideal for machine learning projects focusing on astrophysics or particle physics classification tasks.
