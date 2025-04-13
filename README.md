# Outage Data combined with Renewable Energy Penetration and Weather Conditions

This repository contains datasets for generation unit outages and East-West Interconnector transmission line outages for Ireland. The generation line outage dataset spans from 2015 to 2020, while the transmission line dataset spans from 2015 to 2024.

Two types of datasets have been created for each outage type:

1. Outage data merged with power generation related data
2. Outage data merged with weather conditions

The outage event data in each dataset provides the start date, end date, and the duration of the outage event. The outage data for both types was acquired from ENTSO-E Transparency Platform.

The power generation data consists of the monthly wind generation and solar generation, and the total generation of that month (renewable + non-renewable sources). The RES penetration level (2 - 6) has also been provided for the month that the outage event occured on. The generation data was retrieved from Sustainable Energy Authority Ireland.

The weather data contains the averaged weather conditions across Ireland for each weather condition type which includes minimum temperature, maximum temperature, mean wind speed, global radiation, and relative humidity. This data was sourced from Met Éireann and processed to get the averaged weather conditions of the country. The weather rarity indices for each weather condition type has also been provided.

This dataset can be used for analysing power system resilience, and the datasets can merged together for further analysis e.g. Outage data merged with the weather conditions of that day and the wind and solar generation for the month of the outage occurrence.
