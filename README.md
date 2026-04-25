# Colombia Growth Accounting and Structural Change

This project studies long-run productivity growth and structural transformation in Colombia using aggregate and sector-level data.

The analysis combines growth accounting methods with sectoral productivity decomposition to understand the contribution of capital deepening, human capital, total factor productivity, and labor reallocation to Colombia's economic performance.

## Objective

To analyze Colombia's long-run growth dynamics by combining aggregate productivity measures with sector-level structural change indicators.

## Data

The project uses:

- Penn World Table data for aggregate GDP, capital, employment, hours, human capital, and TFP
- GGDC 10-Sector Database for sectoral value added and employment
- Colombian National Accounts data from DANE for macroeconomic aggregates

## Methodology

The notebook implements:

- Aggregate growth accounting decomposition
- Labor productivity analysis per worker and per hour
- Capital-output ratio analysis
- Sectoral productivity growth estimation
- Reconstructed aggregate productivity from sectoral data
- Comparison between aggregate and sectoral productivity measures
- Shift-share decomposition of labor productivity growth
- Baumol-style analysis of productivity growth and employment reallocation
- Visualization of sectoral productivity and employment shares over time

## Key Technical Features

- Cobb-Douglas growth accounting framework
- Capital deepening decomposition using the capital-output ratio
- Sector-level productivity construction
- Long-run subperiod comparisons
- Structural transformation diagnostics
- Productivity-employment reallocation analysis
- Reproducible figure generation

## Tools

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Excel-based macroeconomic datasets

## Repository Structure

```text
notebooks/
data/
figures/
