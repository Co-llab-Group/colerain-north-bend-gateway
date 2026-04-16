# Colerain-North Bend Gateway

Phase Zero pre-development feasibility assessment for a 2.55-acre, 15-parcel assemblage at Colerain Ave & North Bend Rd, Mount Airy, Cincinnati OH.

**[View the Site Workbook](https://co-llab-group.github.io/colerain-north-bend-gateway/)**

## Site

- **Location:** Colerain Ave & North Bend Rd, Mount Airy, Cincinnati OH 45224
- **Size:** 2.55 acres / 15 parcels
- **Zoning:** CC-P-B / CC-M-B (85 ft height, no FAR, 700 sf/unit density)
- **Overlays:** QCT (Tract 85.01), CRA Expand (75% / 12yr), Hillside
- **Control:** HCLRC at $1 nominal acquisition

## Scenarios

| Scenario | Units | Buildings | TDC | LIHTC Equity | Gap |
|----------|-------|-----------|-----|-------------|-----|
| Starter | 57 | 2 | $28.9M | $20.2M | ($4.3M) |
| Right-Sized | 87 | 2 | $38.8M | $27.2M | ($5.3M) |
| Three Buildings | 131 | 3 | $52.7M | $37.0M | ($5.8M) |
| Max Density | 165 | 3 | $60.5M | $42.5M | ($5.1M) |

## Structure

```
index.html              # Interactive site workbook (all tabs)
renderings/             # Site plan, terrain, concept images
finance/                # Inputs (facts, assumptions, zones, scenarios)
  runs/                 # Calculator-backed engine output
  exports/              # Downloadable workbook (.xlsx)
data/                   # Parcel reference data
```

## Data Sources

- **Parcels:** Hamilton County Auditor via CAGIS API
- **Topography:** USGS 3DEP 1m DEM + CAGIS LiDAR
- **Zoning:** Cincinnati Municode, confirmed against CAGIS zoning layer
- **Rents:** CoStar Cincinnati Q1 2026, Mt. Airy submarket
- **AMI Limits:** HUD FY2025 Income Limits, Hamilton County
- **QCT:** HUD QCT2026 dataset, Tract 85.01
- **Construction Costs:** RS Means 2026, Cincinnati metro adjustment

---

Prepared by [The Co-Llab Group](https://github.com/Co-llab-Group) | Phase Zero Services | April 2026
