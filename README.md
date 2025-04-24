# IRRMAP Dataset

This repository provides environmental and agronomic data within the IRRMAP Dataset.

## Overview

The IRRMAP Dataset contains information about soil moisture, irrigation amount, rainfall, evapotranspiration, crop coefficient, humidity, wind speed, and solar radiation over 5000 days, considering a seasonal climate to mimic a South European environment. The dataset can be used to develop systems that autonomously predicts soil moisture content and irrigation amount using neural network models.

IRRMAP is meant to support data-driven modeling, particularly for applications in precision irrigation and deep learning-based water management systems, as it integrates the main physical processes and information that influence soil moisture and irrigation variability. The following Table presents the features within the dataset. It must be noticed that each record corresponds to a specific daily timestamp, aiming to assess the soil-water-atmosphere interaction.

| Features           | Description                                | Units        |
| ------------------ |--------------------------------------------| ------------:|
| Timestamp          | Date of observation                        |   YYYY-MM-DD |
| Soil Moisture      | Volumetric soil water content              |            % |
| Irrigation Amount  | Daily irrigation water applied             |     $mm/day$ |
| Rainfall           | Daily precipitation                        |     $mm/day$ |
| Evapotranspiration | $ET_0$                                     |     $mm/day$ |
| Crop Coefficient   | Value representing the crop type and stage |            / |
| Temperature        | Daily mean air temperature                 |           °C |
| Humidity           | Relative humidity                          |            % |
| Wind speed         | Wind velocity at 2 meters high             |        $m/s$ |
| Solar radiation    | Total incoming solar radiation             | $MJ/m^2/day$ |


The core components of the daily soil-water balance include direct water inputs, and the terrain's response. Such features are intended to assess the soil moisture dynamics and guide irrigation decisions. The Soil Moisture represents the terrain's response within the soil-water balance, as it depicts the volumetric soil water content in the root zone. Such features increase as a function of the previous moisture conditions, i.e., incoming water through rainfall and irrigation. The decrease is due to evapotranspiration and percolation.

## Acknowledgements

## Cite this Dataset

Please cite this paper if you want to use this dataset in your research (papers, book chapters, conference proceedings, software, etc)

TBA

## Contacts

- Laura Romeo: laura.romeo@stiima.cnr.it
- Antonio Petitti: antonio.petitti@stiima.cnr.it
