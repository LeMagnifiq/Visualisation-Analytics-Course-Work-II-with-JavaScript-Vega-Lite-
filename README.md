# CST4060 – Visualisation Analytics Course Work II
### Data Visualisation with JavaScript
**YAHAYA, Suleyman Olushola.**

#### Overview
This repository contains a data visualisation project for the Boonsong Lekagul Wildlife Preserve's hydrology data from 1998 to 2016. The project utilises Vega-Lite for visualisation. We aim to understand trends, anomalies, and potential threats in chemical contamination that could affect wildlife, particularly the Pipit species.

#### Dataset
The data (CSV format) consists of five columns: Identification number for the record, measured value for the chemical or property in the record, the location of the readings, dates of readings, and the chemicals or water properties measured in the record. In total, we have 13,6825 data points across 104 measures.

#### Visualisation Findings
**Task 1: Chemical Contamination Trends**
We investigate the claims of pollution by focusing on measures of some of the most dangerous chemicals to wildlife:

- Biochemical Oxygen: A high demand level was found in the Kohsoom region in 1998 and 2002, while other areas maintained reasonably low levels until a rise in Tansee in 2013.
- Mercury: All locations saw a slow increase until 2006, with a significant rise in Somchair and Busarakhan in 2009, and a similar jump in Boonsrii and Kohsoom.
- Nickel: High levels of Nickel were present in all locations from 1998 to 2001, before dropping to normal levels. An exception was the Kohsoom region, which saw an uptick in 2006.
- Arsenic: A slow but steady rise can be seen across most of the locations except for a significant rise in Busarakhan up until 2004 and Boonsri in 2004, with a sharp decline in 2012.

**Task 2: Data Quality and Uncertainty**
Data collection started at different years across locations, with three locations only beginning readings in 2009. Inconsistencies in readings were corrected by replacing any values beyond the fourth quartile range with the average.

**Task 3: Wildlife Concern**
High levels of Nickel, Arsenic, and Mercury could threaten the survival of wildlife, particularly the Pipit species. Moreover, an increase in Biochemical Oxygen demand could lead to rapid oxygen depletion in the water, which could be detrimental to aquatic life.

#### Conclusion
The chosen visualisation techniques served the data analysis objectives well, with line charts for trend analysis and heatmaps for data density. There were some data inconsistencies, possibly due to data collection resource constraints or water sensor malfunctions. The potential chemical threats to wildlife call for further investigation and possibly immediate intervention to ensure the survival of the species in the Preserve.
