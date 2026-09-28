This repository contains HTML and Javascript code to create on the fly hydrographs using the USGS and NWPS API. 

**simple.html** - Plots continuous USGS stage/discharge data and NWM forecasts (if location is on NWPS) in a 2 column format 

**historicalStatPlot.html** - recreates previous USGSWaterWatch plots for daily flow percentiles and cumulative annual flow totals

To save on making calls to the USGS API, Historical statistics for MARFC Forecast points are generated and saved into the /stats/ dir by Forecast group. 
These are generated with the python notebook script linked [here](https://colab.research.google.com/drive/1e9DPnVX8qI0daPs2DXGw0K20bn5fHdAf?usp=sharing).
