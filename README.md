# Kepler exoplanet exploration

Kepler Space Telescope has collected data from deep space which confermed the existance of over 2600 planets outside the solar system.

**Data source:** NASA-curated [Kaggle dataset](https://www.kaggle.com/nasa/kepler-exoplanet-search-results).

The goal of this project is to build a machine learning model which can predict an exoplanet based on data provided by Kepler.

**Labels:** 
"koi_disposition" with three distinct values - CANDIDATE, FALSE POSITIVE, CONFIRMED 

**Important features (from highest to lowest):**

* koi_fpflag_nt: Not Transit Like Flag
* koi_fpflag_co: Centroid Offset Flag	
* koi_fpflag_ss: Stellar Eclipse Flag
* koi_model_snr: Transit Signal-to-Noise
* koi_fpflag_ec: Ephemeris Match Indicates Contamination Flag