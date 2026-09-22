# LandSight Ohio property-data samples

Free five-record previews of completed **Franklin County, Ohio** property research datasets from LandSight Solutions LLC, maker of ParcelMetric.

**[Inspect coverage and buy a one-time download](https://www.landsightsolutions.com/data)** — no subscription. The full files are paid curation and GIS enrichment of public source facts; this repository contains samples only.

| Dataset | Full record count | One-time price | Free CSV |
| --- | ---: | ---: | --- |
| Land and building lots, all acreage | 12,791 | $19 | [Sample](samples/franklin-land.csv) |
| Two- and three-family properties | 13,108 | $19 | [Sample](samples/franklin-residential.csv) |
| Commercial and industrial properties, all acreage | 29,604 | $19 | [Sample](samples/franklin-commercial.csv) |
| Large-parcel screen, 20+ acres | 57 | $9 | [Sample](samples/franklin-20plus.csv) |

The three sector files contain **55,503 distinct parcels** and cost **$39 together**. Every record has a recorded owner name. 55,411 records have usable geometry and school context; 55,356 have at least 99.9% coverage from retrieved FEMA flood polygons. Zoning coverage varies and is reported per parcel. The smaller 57-record pack overlaps the sector files.

## Included fields

- Parcel IDs, recorded owner names, available tax mailing and site addresses.
- County tax-use class, acreage, assessment and recorded-sale fields.
- Full-polygon FEMA intersections: flood zones, mapped coverage, SFHA area/percentage and floodway percentage.
- Available local zoning codes, source links and overlap coverage.
- Census school districts; nearest physical NCES public-school location and straight-line distance.
- Nulls and source-invalid parcel geometry explicitly retained as quality flags.

The full purchases include CSV, GeoJSON, per-parcel overlap evidence, provenance and methodology. See the product pages for complete measured coverage before purchasing. These are research files for real estate, construction, property operations and GIS work.

## Sources and dates

County records for the sector files were retrieved September 22, 2026. The small pack uses September 21 county records with September 22 enrichment. Retrieval date is not the update date of each source record.

- [Franklin County parcel service](https://gis.franklincountyohio.gov/hosting/rest/services/ParcelFeatures/Parcel_Features/FeatureServer/0)
- [FEMA National Flood Hazard Layer](https://hazards.fema.gov/arcgis/rest/services/public/NFHL/MapServer/28)
- [NCES 2024–25 public-school locations](https://nces.ed.gov/opengis/rest/services/K12_School_Locations/EDGE_ADMINDATA_PUBLICSCH_2425/MapServer/1)
- [Census TIGERweb ACS 2024 school districts](https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_ACS2024/MapServer/14)

Municipal and township zoning sources are documented in each product's provenance. Overlapping polygons are unioned for coverage calculations; source-invalid parcel geometry receives no spatial enrichment.

## Scope and sample use

These public samples may be used to evaluate the files for internal business research. No exclusive rights to government source facts are claimed. Full-pack purchase terms allow internal work and client projects.

Official GIS screening does not certify title, legal access, utility capacity, approved use, physical vacancy, sale availability, school assignment or project suitability. Nearest school is not guaranteed attendance. FEMA overlap is not a lender flood certificate. Public tax-use vacancy coding is not a site inspection. See each product's methodology for field definitions and limits.

Published by [LandSight Solutions LLC](https://www.landsightsolutions.com/data).
