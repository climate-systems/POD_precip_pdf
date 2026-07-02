# POD_precip_pdf
This POD calculates the precipitation probability distributions linked to major system types across the globe by using high-resolution satellite observations, reanalysis and CMIP6 model simulations. For precipitation, its probability density function (PDF) has a form closer to a Gamma distribution, with a scale-free regime at low intensities and a scale-dependent regime at high intensities.
Precipitation PDFs can be characterized by two parameters: a power-law exponent $\tau$ governing the low to moderate precipitation range, and a probability-decay intensity scale P<sub>L</sub> governing the high-intensity precipitation range, providing a more tailored representation than mean and standard deviation. The precipitation PDFs can be calculated for various weather systems, seasons, and regions. The data used in this POD includes:

- Integrated Multi-satellitE Retrievals for GPM (IMERG) Final Run product, Version 06B
- ECMWF ERA5 reanalysis
- A minimum of one year of data at 3-hourly temporal resolution is recommended to ensure a sufficient sample size.
- This POD is designed for models with relatively high horizontal resolution (≤ 0.5°). Conservative regridding is applied by default to ensure consistent comparisons between model outputs and the observational reference (GPM-IMERG + ERA5).
- Detailed descriptions of the POD are documeneted in "diagnostics/MCS_precip_buoy_stats/doc/MCS_precip_buoy_stats.rst"
