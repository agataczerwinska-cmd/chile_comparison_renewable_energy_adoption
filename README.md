# Renewable Energy in Latin America: Chile in Regional Context

Comparative analysis of renewable electricity adoption in Chile, Argentina, 
Brazil, Colombia, and Peru (1990-2022), looking at both overall renewable 
share and the specific mix of energy sources behind it.

## Background

Built as a self-directed learning project bridging my ESG/sustainability 
reporting background (CDP) with hands-on data analysis using pandas and 
matplotlib in Google Colab.

## Question

How does Chile's renewable energy adoption compare to its Latin American 
neighbors — and what specific sources (hydro, solar, wind) make up that mix?

## Data source

**Our World in Data — Energy Dataset** (via Kaggle: "World Energy Consumption")

Initially started with World Bank ESG data, which only provided an aggregate 
"renewable energy consumption %" figure. Switched to this dataset because it 
breaks down electricity generation by specific source (hydro, solar, wind, 
coal, gas, oil, nuclear) and covers a longer, more recent time range 
(1990-2022 vs. 1990-2014).

## Finding 1: Renewable share over time (1990-2022)

Renewable electricity share **declined** across all five countries from 1990 
through the mid-2010s — likely reflecting energy demand growth (industrialization, 
mining, population growth) outpacing renewable capacity additions. From roughly 
2018 onward, most countries — especially Chile and Brazil — show a renewed 
upward trend, coinciding with the global acceleration in solar and wind investment.



## Finding 2: Electricity mix by source (2022)

Brazil and Colombia lean heavily on hydroelectric power (60-75% of their grid). 
Argentina relies primarily on gas (~55%). **Chile stands out for having the 
most diversified electricity mix** of the five — meaningful contributions from 
hydro, solar (~17%), and wind (~10%), alongside continued coal and gas use.

![Electricity mix 2022](latam_electricity_mix_2022.png)

## Conclusion

Chile's diversified 2022 electricity mix is the direct result of the recent 
upward trend visible in Finding 1 — its solar and wind shares are the product 
of deliberate, recent capacity investment (leveraging strong solar resources 
in the Atacama Desert), not long-standing infrastructure like hydro. This 
contrasts with Brazil and Colombia, whose renewable share, while high, comes 
from a single legacy source rather than a diversified portfolio — a distinction 
that matters for energy security and grid resilience, not just renewable %.

## Tools used

Python, pandas, matplotlib, Google Colab

## Files in this repo

- `latam_renewables_analysis.ipynb` — full notebook with code and outputs
- `latam_renewables_trend_1990_2022.png` — renewable share over time chart
- `latam_electricity_mix_2022.png` — electricity mix by source chart
