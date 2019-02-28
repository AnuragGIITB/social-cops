# social-cops
SociaCops Data Science Internship Task

Challenge 1: Agriculture Commodities, Prices & Seasons

Objective:
1. Test and filter outliers.
2. Understand price fluctuations accounting the seasonal effect
    a. Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities
    b. De-seasonalise prices for each commodity and APMC according to the detected seasonality type
3. Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised
4. Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

Variable description:
1. msprice- Minimum Support Price
2. arrivals_in_qtl- Quantity arrival in market (in quintal)
3. min_price- Minimum price charged per quintal
4. max_price- Maximum price charged per quintal
5. modal_price- Mode (Average) price charged per quintal
