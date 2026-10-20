# Global Comparison of Natural and Planted Forest Engineering Resilience from MODIS Time Series

**Erzheng Liang**  
Master of Science in Geospatial Data Science, The University of Hong Kong · July 2026

[Read the thesis (PDF)](Master_Thesis.pdf)

## Abstract

Forests regulate carbon, water and energy exchanges between land and the atmosphere, support biodiversity, and provide essential ecosystem services. Under climate change, a central question is whether forests can maintain their functions and recover following disturbances. This capstone project compares the engineering resilience of natural and planted forests at the global scale using MODIS vegetation-index time series. The primary indicator is the first-order autocorrelation (AR1) of residual NDVI time series obtained after quality filtering, gap filling, and STL decomposition of long-term trends and seasonality. Higher residual AR1 is interpreted as stronger anomaly persistence, slower recovery, and lower engineering resilience.

The analysis first maps long-term AR1 across global consistent forests. The consistent-forest mask is constructed from MCD12Q1 IGBP forest classes 1–5, requiring forest classification in at least 90% of years from 2001 to 2024 and a consistent-forest fraction of at least 50% within each 0.01° grid cell. Natural and planted forests are then compared using a paired 0.25° grid design based on 30 m forest-type fractions. The paired difference is defined as ΔAR1 = AR1_planted − AR1_natural. Under the main setting, with 70% forest-type purity and at least 10 pixels per forest type, 13,994 paired cells are identified. The mean NDVI ΔAR1 is 0.0306 and the median is 0.0172; 70.7% of paired cells have higher AR1 in planted forests. Robustness checks using EVI and kNDVI yield consistently positive mean differences. The reverse pattern occurs in 29.3% of NDVI paired cells, while 11.1% of all paired cells show the reverse sign across all three indices. Random forest models, SHAP values, and partial dependence plots identify associations of fire disturbance and temperature-related gradients with spatial variation in ΔAR1. The results provide global-scale evidence that natural and planted forests have distinguishable time-series resilience patterns and that their establishment and management pathways are relevant to forest resilience assessment.
