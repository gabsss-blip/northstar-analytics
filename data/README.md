# NorthStar Urban Mobility and Logistics — Analytics Project

## Module: Databases and Analytics — S2 2026

## GitHub Repository
https://github.com/gabsss-blip/northstar-analytics

## Project Overview
This project analyses operational inefficiencies at NorthStar Urban Mobility 
and Logistics using SQL, R, Python, and MongoDB Atlas. The analysis identifies 
root causes of delivery failures, driver performance issues, hub inefficiencies, 
and customer complaint patterns across NorthStar's urban logistics network.

## Repository Structure
| File | Description |
|------|-------------|
| `01_Python_Cleaning.ipynb` | Data cleaning, zone standardisation, missing value treatment, and visualisations |
| `02_SQL_in_R.ipynb` | SQL queries in R using sqldf — delivery, hub, driver, and cost analysis |
| `03_R_Analytics.ipynb` | Statistical analysis, correlation matrix, and visualisations in R |
| `04_MongoDB.ipynb` | MongoDB Atlas NoSQL database design, CRUD operations, and query optimisation |

## Datasets
| File | Rows | Description |
|------|------|-------------|
| `customers.csv` | 650 | Customer profiles with loyalty and engagement scores |
| `orders.csv` | 1,250 | Orders across all service types and zones |
| `deliveries.csv` | 950 | Delivery records linking drivers, vehicles, and hubs |
| `drivers.csv` | 170 | Driver profiles with experience and training scores |
| `vehicles.csv` | 120 | Vehicle records with battery health and maintenance status |
| `hubs.csv` | 8 | Operational hubs across NorthStar zones |
| `incidents.csv` | 280 | Incident records linked to deliveries |
| `complaints.csv` | 320 | Customer complaints with resolution tracking |
| `app_events.csv` | 640 | Mobile app interaction events |

## Key Findings
- 35.2% of deliveries are delayed or failed
- Central zone has the highest failure rate at 19%
- 30% of vehicles are currently in repair
- Delay is the most common complaint type
- Drivers with lower training scores show higher failure rates

## Technologies Used
- Python (Pandas, NumPy, Matplotlib)
- R (sqldf, ggplot2, dplyr, corrplot)
- MongoDB Atlas (PyMongo)
- Google Colab
- GitHub

## MongoDB Atlas
- Database: `northstar_db`
- Collections: `customer_cases`, `deliveries`, `hubs`
- Customer cases embed orders, complaints, and app events into single documents
