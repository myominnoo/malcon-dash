# The MalCon Monitoring Dashboard

This [MalCon Monitoring Dashboard](https://myominnoo.github.io/malcon-dash/) provides an overview of the progress of the health facility survey 2021 conducted by the Malaria Control Section (MalCon) at the Papua New Guinea Institute of Medical Research (PNGMIR). This dashboard is built in the framework of reproducibile research using Rmarkdown and GitHub action workflows.

**Data**

The input data for this dashboard are from the ODK Central platform that is hosted by Swiss Tropical and Public Health Institute. The data and dashboard are refreshed on a daily basis.

**Packages**

- Dashboard interface - the `flexdashboard` package.
- Visualization - the `plotly` package for the plots and mapview package for the map
- Data manipulation - `dplyr`, and `tidyr`
- Tables - the `DT` package

**Credits**
The projects by [Rami Krispin](https://github.com/RamiKrispin/) inspires this dashboard. 