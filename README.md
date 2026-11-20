### Hi, I'm Raphel 👋

**Hydrological modeller | Geoscience, GIS, remote sensing and AI for water resources and environmental risk management.**

<p align="center">
  <a href="https://github.com/raphel-abine/aire-pdm-flood-forecasting"><img src="https://raw.githubusercontent.com/raphel-abine/aire-pdm-flood-forecasting/main/figures/forecast_skill.png" alt="PDM flood forecast skill and Boxing Day 2015 forecasts on the River Aire" width="90%"></a>
</p>
<p align="center"><sub><b>Flood forecasting on the River Aire:</b> forecast skill by lead time, and forecasts of the Boxing Day 2015 flood issued 24 to 6 h ahead</sub></p>

I'm a UKRI-funded Doctoral Researcher at **Brunel University London**, developing deep-learning models that integrate remote sensing and environmental data to improve streamflow prediction in mountain catchments, with a particular focus on the contribution of snowmelt.

My route into hydrology started in geology, which I built on through GIS and remote sensing, followed by hydrogeology and groundwater modelling. That background shapes how I approach modelling: I start with what the geology, soils and gauging records can tell me, and test a model against the available evidence before I trust its results.

In every project I aim for **quality control data, and results written up so a decision-maker can act on them.**

**🔭 Next:** building an FEH-style flood frequency analysis that carries rating-curve uncertainty into design flood estimates.  
**🤝 Open to:** conversations, research collaborations and opportunities across hydrology, groundwater, flood risk, climate-risk modelling, geospatial science and environmental AI. Also interested in industry engagement and placement in 2027.

---

### What I work on

**💧 Groundwater and hydrogeology**

Groundwater flow modelling in **MODFLOW 6**, including steady-state and transient calibration, sensitivity analysis and **source protection zone delineation** around abstraction wells. Hydrogeological site characterisation with **geophysics (ERT, GPR, EMI)**, covering different aquifers, freshwater lenses and saltwater intrusion. Groundwater chemistry and soil-water modelling (**HYDRUS-1D**). Trained at Ghent University (MSc Land and Groundwater Management), with an MSc dissertation on groundwater sustainability in urban Cameroon.

**🌊 Flood forecasting and hydrology**

Conceptual and deep-learning rainfall–runoff models (GR4J, GR6J, PDM, LSTM), real-time error updating, forecast verification against persistence, and rating-curve review using Environment Agency data.

**🛰️ Geospatial and environmental data science**

Advanced **QGIS** and **ArcGIS** user, including ArcGIS StoryMaps (MSc GIS with Distinction; I have also delivered GIS training courses). Python and R pipelines that pull, clean and quality-check large public datasets (CAMELS-GB, EA APIs, Google Earth Engine). GIS and remote sensing for hazard mapping, including landslide susceptibility (prize-winning MSc dissertation).

**📈 Flood and climate risk**

Turning model output into risk-relevant numbers: flood peaks, exceedance of warning thresholds, and the uncertainty in "observed" extremes that drives hazard estimates.

---

### Projects

| Project | What it shows | Headline result |
|---|---|---|
| [**UK rainfall–runoff benchmark**](https://github.com/raphel-abine/uk-rainfall-runoff-benchmark) | GR4J, GR6J (± snow module) and an LSTM ensemble compared on 128 UK catchments (CAMELS-GB), with maps of where each model performs best | The LSTM was best in 110 of 128 catchments, but a snow module closed 66–94% of its lead in the Cairngorms |
| [**Aire PDM flood forecasting**](https://github.com/raphel-abine/aire-pdm-flood-forecasting) | An hourly PDM forecasting system at 1–24 h lead times, plus a rating-curve review using live Environment Agency data | Updating cut the 3 h flood-peak forecast error from 23% to 4%; the largest flood flows carry up to 21% rating uncertainty |

<p align="center">
  <a href="https://github.com/raphel-abine/uk-rainfall-runoff-benchmark"><img src="https://raw.githubusercontent.com/raphel-abine/uk-rainfall-runoff-benchmark/main/figures/maps_best_model.png" alt="Best model in each of 128 UK catchments" width="70%"></a>
</p>
<p align="center"><sub><b>UK benchmark:</b> best model per catchment, and the LSTM's gain over the GR models</sub></p>

Each project is written up as a technical report, with reproducible scripts and all the results tables.

**Coming next:** FEH-style flood frequency analysis with rating uncertainty · a fully scripted UK groundwater model (MODFLOW 6 in FloPy) built from public BGS and EA data, so the code can be shared openly · mangrove change and blue carbon in Cameroon from satellite data.

#### Earlier work (MSc, Ghent University, 2022–2024)

| Project | Methods | Outcome |
|---|---|---|
| Groundwater flow and protection zones, alluvial aquifer | MODFLOW 6 (steady-state and transient), calibration to heads under natural and pumping conditions, sensitivity analysis, advective transport | Protection zones for 24 h and 60 days around a pumping well; zone elongated north-east along high-conductivity gravel |
| Hydrostratigraphy and infiltration potential, Boechout | ERT and GPR surveys, soil profiles | Mapped soil layers, perched aquifers and infiltration potential to support water management |
| Artificial dune and coastal aquifer, Oostaker | ERT, EMI and GPR | Water table at 4–5 m, a developing freshwater lens, and saltwater intrusion deeper than 7.5 m about 36 m inland |
| Soil-water flow under different land uses | HYDRUS-1D, R | Storage, runoff and infiltration compared for forest, grassland and cropland, including compaction scenarios |
| Maize water productivity, Axum (Ethiopia) | FAO AquaCrop, 19-year simulations, 12 management scenarios | Root-zone water balance, yield gaps and drought-driven crop-failure probabilities |
| Lagdo Dam releases and flooding in Nigeria | Hydro-geomorphological analysis, hazard mapping | Flood-risk mapping and stakeholder early-warning recommendations |
| Menchum Falls hydropower (450 MW) | Environmental impact assessment | Impacts on flow regime, biodiversity and communities, with mitigation measures |
| Deforestation and temperature in mountain Cameroon | Satellite imagery and station data | Links between forest loss, temperature variability with elevation, and water resources |

#### Earlier work (MSc GIS, University of Portsmouth, 2019–2020)

- **Hydrology:** hydrological modelling of the Boscastle and Palmer Brook catchments
- **Hazards:** landslide susceptibility analysis with GIS and remote sensing (dissertation, Best MSc Dissertation 2020)
- **Surveying and terrain:** digital surface modelling of Lavington Common, West Sussex, from ground survey data
- **Remote sensing:** degradation of the Mesopotamian Marshes, southern Iraq, from Landsat imagery
- **Coastal and historical GIS:** coastal change, land use and rent charges from the 1846 tithe map of West Wittering
- **Spatial modelling:** habitat suitability for lynx reintroduction in the UK
- **Web GIS:** web mapping of land capability for agriculture in Scotland

---

### Background

- 🎓 **PhD**, Brunel University London (UKRI-funded, 2025–): deep learning for streamflow prediction
- 🎓 **MSc Sustainable Land Management (Land and Groundwater Management)**, Ghent University (Cum Laude): hydrogeology, groundwater modelling (MODFLOW 6), geophysics, groundwater chemistry, soil-water management, EIA
- 🎓 **MSc GIS**, University of Portsmouth (Distinction; Best MSc Dissertation 2020)
- 🎓 **BSc Geology**, University of Buea (Senate award for best graduating student, 2015) 
- 🧑‍🏫 Teaching: delivered GIS training courses; Graduate Teaching Assistant at Brunel
- 💧 Student Member of **CIWEM** · Member of the **AGI**

---

### Tools

**Modelling:** `MODFLOW 6` · `HYDRUS-1D` · `AquaCrop` · `GR4J / GR6J (airGR)` · `PDM` · `LSTM (neuralhydrology, PyTorch)`  
**Field and geophysics:** `ERT` · `GPR` · `EMI` · `soil sampling`  
**GIS and Earth observation:** `QGIS` · `ArcGIS Pro` · `ArcGIS StoryMaps` · `Google Earth Engine` · `GeoPandas`  
**Programming and data:** `Python` · `R` · `pandas` · `numba` · `Git`

---

📫 [LinkedIn](https://www.linkedin.com/in/gistech2021)
