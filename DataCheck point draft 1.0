Data overview

We use multiple country-level datasets that can be aligned by country name (and standardized to ISO-3 codes) to estimate caffeine exposure and compare it to health and social outcomes.

Dataset 1 — Coffee consumption per capita (country-level)

Dataset name: Coffee Consumption by Country (Coffee Consumption Rate)

Link: https://worldpopulationreview.com/country-rankings/coffee-consumption-by-country

Unit: kg per capita (coffee consumption rate), reported for 2023 (one row per country).

Key variables used: Country; Coffee Consumption Rate 2023 (kg/capita).

Shortcomings: Country-level aggregate (ecological); definitions may include multiple coffee product categories; measurement error and cross-country comparability issues; does not directly measure caffeine mg.

Dataset 2 — Tea consumption per capita (country-level)

Dataset name: Tea Consumption by Country (Tea Consumption Rate)

Link: https://worldpopulationreview.com/country-rankings/tea-consumption-by-country

Unit: kg per capita (tea consumption rate), reported for 2022 (one row per country).

Key variables used: Country; Tea Consumption Rate 2022 (kg/capita).

Shortcomings: “Tea” may include culturally distinct beverages (e.g., mate) depending on underlying source definitions; ecological measurement; does not directly measure caffeine mg.

Dataset 3 — Depressive disorders prevalence (country-year)

Dataset name: Share of people living with depressive disorders (age-standardized prevalence)

Link: https://ourworldindata.org/grapher/depressive-disorders-prevalence-ihme

Unit: percent (%) of population; annual country-year panel (1990–2023).

Key variables used: Entity (country); Year; Prevalence (%).

Shortcomings: Model-based estimates (not direct surveillance everywhere); still ecological.

Dataset 4 — All-cause mortality rate (country-year)

Dataset name: Annual death rate from all causes (age-standardized)

Link: https://ourworldindata.org/grapher/age-standardized-deaths-from-all-causes

Unit: deaths per 100,000 people; annual panel (1980–2023).

Key variables used: Entity (country); Year; Death rate (per 100,000).

Shortcomings: Model-based estimates; age-standardization improves comparability but does not remove all bias.

Dataset 5 — Confounders (country-year)

GDP per capita (PPP): https://ourworldindata.org/grapher/gdp-per-capita-worldbank
 (annual panel).

Smoking/tobacco use (% adults): https://ourworldindata.org/grapher/share-of-adults-who-smoke
 (annual panel; 2000–2022).

Alcohol consumption (liters pure alcohol per adult 15+): https://ourworldindata.org/grapher/total-alcohol-consumption-per-capita-litres-of-pure-alcohol
 (annual panel; 2000–2020).

Shortcomings: Different end-years across confounders; will align by choosing a target year and using “nearest prior year” if needed.

How we combine datasets

Standardize country identifiers (ISO-3) and clean numeric columns.

Build a country-year panel for outcomes/confounders.

Convert coffee/tea kg per capita into an “estimated caffeine mg/day” proxy using a transparent conversion factor (sensitivity analysis later).

Merge everything at a chosen analysis year (e.g., 2022), taking the most recent value available at or before that year when needed.
