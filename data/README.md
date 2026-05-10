# NorthStar Dataset

This folder contains the cleaned datasets used for analysis .

## Files
- `customers.csv` — 650 customer records with engagement and loyalty metrics
- `orders.csv` — 1,250 orders across all service types and zones
- `deliveries.csv` — 950 delivery records linking drivers, vehicles, and hubs
- `drivers.csv` — 170 driver profiles with experience and training scores
- `vehicles.csv` — 120 vehicle records with battery health and maintenance status
- `hubs.csv` — 8 operational hubs across NorthStar zones
- `incidents.csv` — 280 incident records linked to deliveries
- `complaints.csv` — 320 customer complaints with resolution tracking
- `app_events.csv` — 640 mobile app interaction events

## Data Quality Issues Fixed
- Inconsistent zone names standardised (North/NORTH/north → North)
- Missing values filled using median imputation or sensible defaults
- All files cleaned and ready for analysis
