# Bureau of Reclamation (bureau-of-reclamation)
Established in 1902, the Bureau of Reclamation is best known for the dams, powerplants, and canals it constructed in the 17 western states. These water projects led to homesteading and promoted the economic development of the West. Reclamation has constructed more than 600 dams and reservoirs including Hoover Dam on the Colorado River and Grand Coulee on the Columbia River.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bureau-of-reclamation/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** government
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Energy
- Federal Government
- Infrastructure
- Water
- Hydrology
- Reservoirs

## Timestamps

- **Created:** 2024-11-30
- **Modified:** 2026-04-23

## APIs

### Reclamation Information Sharing Environment (RISE) API
The RISE API allows users to query Bureau of Reclamation water resource data programmatically, returning JSON objects. For Geospatial and File Upload datasets, only metadata can be queried. For time series datasets, both metadata and data can be queried. Data includes hydrometric measurements, reservoir levels, streamflow, and water quality.

**Human URL:** [https://data.usbr.gov/rise/api](https://data.usbr.gov/rise/api)

**Base URL:** https://data.usbr.gov/rise/api/

#### Tags

- Federal Government
- Water
- Hydrology
- Time Series

#### Features

- Time Series Data
- Hydrometric Measurements
- Reservoir Level Data
- Streamflow Data
- Water Quality Data
- Geospatial Metadata
- JSON Format
- Paginated Results

#### Use Cases

- Water resource planning
- Drought monitoring
- Hydroelectric generation analysis
- Environmental flow studies
- Water rights management
- Climate research

#### Key Endpoints

- `/catalog-item` - Query catalog items
- `/catalog-record` - Query catalog records
- `/location` - Query monitoring locations
- `/parameter` - Query measured parameters
- `/result` - Query time series results
- `/reclamation-region` - Query Reclamation regions
- `/model-run` - Query model run data

## Common Properties

- [Website](https://www.usbr.gov)
- [Portal](https://data.usbr.gov/)
- [Privacy Policy](https://www.usbr.gov/privacy.html)
- [Data Portal](https://catalog.data.gov/dataset?organization=usbr-gov)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
