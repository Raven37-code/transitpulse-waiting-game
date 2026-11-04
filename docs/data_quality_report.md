# TransitPulse — Data Quality Report

## Dataset Checked
`data/raw/bus_arrivals.csv`

## Checks Performed

| Check | Result |
|---|---|
| Total arrival records | 10 |
| Missing values | 0 |
| Duplicate arrival IDs | 0 |
| Invalid route IDs | 0 |
| Invalid stop IDs | 0 |

## Findings
The 10 simulated bus arrival records passed the initial data quality checks.

All records contain the required information, each arrival has a unique ID, and the route and stop IDs match the reference datasets.

## Limitations
This is a small simulated dataset. Passing these checks does not guarantee that all arrival times are accurate or that the data represents real bus operations.

## Conclusion
The dataset is suitable for our initial learning exercises and exploratory analysis.