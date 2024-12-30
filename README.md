# IHDS-Spatial-Visualization
This project uses Indian Human Development Survey(IHDS), round 2 data to spatially analyze untouchability practices at the district level in India. It includes Stata code for data processing and visualization, culminating in a thematic map that categorizes districts based on the percentage of households practicing untouchability.

# The analysis is based on three key survey questions, focusing on:

1. Households experiencing untouchability in the last 5 years.
2. Households practicing untouchability.
3. Issues with Scheduled Caste members entering kitchens or sharing utensils.

## Key Features
- **Data Preparation**: Aggregates and calculates district-level percentages of households practicing untouchability.
- **Categorization**: Classifies districts into percentage ranges (e.g., `0%`, `<5%`, `5%-10%`, etc.).
- **Visualization**: Generates a thematic map showing prevalence, with darker shades indicating higher percentages.

## How to Use
1. Load IHDS data and run the provided Stata code.
2. Ensure district and state boundary files are in the working directory.
3. View the generated map to analyze spatial patterns.

## Repository Structure
```
|-- README.md            # Project documentation (this file)
|-- StataCode.do         # Stata script for data processing and visualization
|-- IHDS_collapse.dta    # Aggregated district-level data
|-- india_districts_db.dta # District boundary geospatial data
|-- india_states_coords.dta # State boundary geospatial data
|-- Outputs/             # Folder for storing generated maps
```

## Notes
- The IHDS data is used in compliance with its terms.
- Boundary files must align with IHDS data for accurate mapping.

For questions, feel free to reach out via GitHub or email.

