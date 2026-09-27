---
name: Data / material / brand curation
about: Add or correct material, garment, brand, or supplier data
title: "[data] "
labels: ["data", "good first issue"]
assignees: []
---

## Data class

- [ ] Material (water / CO2 / energy / chemical / biodegradability scores)
- [ ] Garment (category, weight, lifespan, care)
- [ ] Brand (environmental / labour / animal ratings, certifications)
- [ ] Supplier / facility (via Open Apparel Registry)
- [ ] Safety notice / recall feed
- [ ] Other:

## Source citation

<!-- Every data point needs a citable source. Link the LCA study, brand
     transparency report, certification registry entry, or regulatory notice.
     Uncited PRs will be returned for sourcing. -->

- Source URL:
- Publication date:
- Methodology / standard (e.g. GHG Protocol, ISO 14040, EU ECHA):

## Proposed entry

<!-- Paste the structured data. kyaml/yaml preferred; JSON acceptable. -->

```yaml
# example:
name: "…"
water_liters_per_kg: …
co2_kg_per_kg: …
energy_mj_per_kg: …
# …
```

## Confidence / provenance notes

<!-- Any caveats (regional variation, data quality tier, modelled vs measured). -->
