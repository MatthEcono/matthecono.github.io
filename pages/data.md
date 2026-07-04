---
layout: single
title: "Data & Spatial"
permalink: /data/
author_profile: true
---

# Data & Spatial

Reproducible datasets and spatial tools for research on health, climate, and regional
economics in Brazil.

## Harmonised climate–arbovirus panel (Brazil, 2015–2025)

A single, harmonised **municipal-monthly** database for Brazil integrating climate
(ERA5-Land and BR-DWGD), arbovirus cases (dengue, Zika, chikungunya, from SINAN),
drought indices, hospital and outpatient burden (SIH/SIA-SUS), municipal public finance,
sanitation, entomology, population, and vegetation (NDVI). Every layer is documented, with
its source, extraction method, and aggregation rule, and is reproducible from raw data.

The dataset (code on GitHub, raw data on Zenodo) is being prepared for release together with
a data descriptor.

## Interactive aggregation portal *(in development)*

A browser-based portal to explore and download the panel: choose the variables, the spatial
level (municipality → micro-/meso-region → state → region → Brazil) and the temporal step
(monthly → quarterly → half-yearly → yearly). The portal aggregates on the fly — summing
extensive variables and taking population-weighted means of intensive ones — and offers rates
per 1,000 / 100,000 inhabitants for counts, with export to CSV.

## Spatial methods

Work in this area uses georeferenced microdata and spatial econometrics (exploratory spatial
data analysis, spatial autoregressive and Tobit models) applied to health outcomes and
regional inequalities.
