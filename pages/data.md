---
layout: single
title: "Data & Spatial"
permalink: /data/
author_profile: true
---

Reproducible datasets and spatial tools for research on health, climate, and regional
economics in Brazil. *Click each item to expand.*

<style>
  .ds-item{border:1px solid rgba(128,128,128,.3);border-radius:8px;margin:12px 0;overflow:hidden}
  .ds-item>summary{cursor:pointer;padding:12px 16px;font-weight:700;list-style:none;font-size:1.05em}
  .ds-item>summary::-webkit-details-marker{display:none}
  .ds-item>summary::before{content:"▸ ";color:#888}
  .ds-item[open]>summary::before{content:"▾ "}
  .ds-item>summary:hover{background:rgba(128,128,128,.08)}
  .ds-body{padding:4px 16px 16px}
</style>

<details class="ds-item">
<summary>GHRN — Global Health Research Network map (University of York)</summary>
<div class="ds-body">
<p>Interactive map of the Global Health Research Network (GHRN), built during a doctoral visit
at the University of York. It geolocates the network's projects and partners, letting users
explore the geographic footprint of the research portfolio.</p>
<p>➡ <a href="https://maps-visualization.github.io/uoy/" target="_blank" rel="noopener">Open the interactive map</a></p>
</div>
</details>

<details class="ds-item">
<summary>Harmonised climate–arbovirus panel &amp; aggregation portal (Brazil, 2015–2025)</summary>
<div class="ds-body">
<p>A single, harmonised <strong>municipal-monthly</strong> database for Brazil integrating climate
(ERA5-Land and BR-DWGD), arbovirus cases (dengue, Zika, chikungunya, from SINAN), drought
indices, hospital and outpatient burden (SIH/SIA-SUS), municipal public finance, sanitation,
entomology, population, and vegetation (NDVI). Every layer is documented — with its source,
extraction method, and aggregation rule — and is reproducible from raw data. The dataset (code on
GitHub, raw data on Zenodo) is being prepared for release together with a data descriptor.</p>
<p>An <strong>interactive aggregation portal</strong> <em>(in development)</em> lets you explore and
download the panel: choose the variables, the spatial level (municipality → micro-/meso-region →
state → region → Brazil) and the temporal step (monthly → quarterly → half-yearly → yearly). It
aggregates on the fly — summing extensive variables and taking population-weighted means of
intensive ones — and offers rates per 1,000 / 100,000 inhabitants for counts, with export to CSV.</p>
</div>
</details>
