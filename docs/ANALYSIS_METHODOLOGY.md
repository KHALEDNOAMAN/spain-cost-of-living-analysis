# Spain Cost of Living - Methodology Guide

## Data Sources
| Source | Data | Format |
|--------|------|--------|
| Numbeo | Cost indices | CSV |
| INE | Official statistics | API |
| Idealista | Rent prices | Scraped |

## Analysis Pipeline
```
Raw Data --> Cleaning --> EDA --> Visualization --> Insights
               |           |            |
          Missing Values  Correlations  Matplotlib
          Outliers        Distributions Seaborn
```

## Key Metrics
| Metric | Description |
|--------|-------------|
| Rent Index | Average monthly rent by city |
| Salary Ratio | Rent as % of median salary |
| Affordability | Composite cost score |
| Quality of Life | Cost vs amenities balance |

## Tools Used
- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebooks