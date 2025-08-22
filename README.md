**US Birth Outcomes Analysis (2016–2018)**

Dataset
Source: bigquery-public-data.sdoh_cdc_wonder_natality.county_natality

1,878 rows | 626 counties | 3 years (2016–2018)

**Data Overview**

No missing values in key columns (birth weight, mother’s age, gestation weeks).
Coverage: 626 counties, 3 years.

**KPIs & EDA**

Births: Declined YoY (2017: –2.29%, 2018: –1.65%).
Mother’s Age: Stable (~28 years).
Birth Weight: Stable; minor dip in 2018.
BMI: Pre-pregnancy BMI increased over time.
Prenatal Care: Lowest in Nueces County, TX (8.93 weeks).
Highest Birth Weight: Unidentified Counties, AK.
Lowest Birth Weight: Hinds County, MS.

**Insights**

**Top Counties**
LA County (CA), Harris (TX), and Cook (IL) led all 3 years.
Births are concentrated in major metros.

**Top States (per Year)**
CA, TX, and NY consistently lead.
These three states dominate national births.

**Cumulative Births**
2016: ~3.95M → 2018: ~11.59M.
Over 11.5M births in 3 years.

**Total State Births (2016–18)**
CA: 1.41M, TX: 1.16M, NY: 0.69M.
California alone = ~12% of US births.

**Birth Weight Distribution**
p25: ~3235g, p50: ~3278g, p75: ~3320g.
Stable and consistent across years.

**Summary**

This project explores U.S. natality data (2016–2018) through SQL-based EDA, KPIs, and advanced analytics (ranking, cumulative trends, rolling averages, percentiles). Findings show consistent declines in births, stable maternal age, and highly concentrated birth trends in large states and counties.
