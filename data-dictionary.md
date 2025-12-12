# Data Dictionary

## Dataset Information
- **Source:** Our World in Data
- **Period:** January 2020 - March 2023
- **File:** full_data.csv

## Key Variables

| Variable | Description | Type |
|----------|-------------|------|
| location | Country income group (High/Low) | Categorical |
| weekly_deaths | Number of COVID deaths per week | Numeric |
| date | Week ending date | Date |

## Income Group Classification

**High-Income Countries:**
- GNI per capita > $12,696
- Examples: USA, UK, Germany, Japan

**Low-Income Countries:**
- GNI per capita < $1,046
- Examples: Afghanistan, Chad, Ethiopia

## Data Cleaning
- Removed missing values
- Filtered to only High/Low income groups
- Final dataset: 2,244 observations
