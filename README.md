# Housing Price Analysis (2000–2025)
This project is a data analysis exploration of U.S. housing price trends using the Zillow dataset. The dataset covers monthly housing prices across U.S. metros and states from 2000 to 2025.

## The main goals of this project were:

To clean and reshape the dataset into a tidy format

To visualize housing price trends at the national, state, and city levels

To compute long-term growth and identify the fastest-growing housing markets

## Data Source

Dataset: Zillow Housing Prices (CSV)

Shape: ~895 regions × 312 columns (monthly data)

Time Range: January 2000 → July 2025

## Methods & Tools

Python: pandas, matplotlib, seaborn

Data Cleaning: handled missing values, reshaped from wide → long format

Analysis: descriptive stats, growth calculations, percent change since 2000

Visualizations: line plots of national, city, and state-level trends

## Key Results
### 1. National Trend

Housing prices have shown a steady increase from 2000 to 2025.

The 2008 housing crash is visible as a dip in prices, followed by recovery.

Prices accelerated significantly after 2020, especially post-pandemic.

### 2. City Comparisons

New York vs Los Angeles: Both showed strong upward trends, with LA overtaking NY in price growth after 2015.

Major Metros (NY, LA, Chicago, Dallas, Miami):

Miami saw sharper growth compared to Chicago and Dallas.

Chicago’s housing market remained relatively flat compared to others.

### 3. Fastest-Growing Metros (2000–2025, % Growth)

#### Top 5:

Kapaa, HI → +539%

Kahului, HI → +426%

Clewiston, FL → +412%

Prineville, OR → +410%

Steamboat Springs, CO → +388%

These are mostly smaller or lifestyle-driven markets, not the largest metros.

### 4. State-Level Trends

California (CA): consistently the most expensive state average.

Texas (TX): remained affordable but has been rising steadily.

Florida (FL): rapid post-2020 growth, similar to CA in acceleration.

New York (NY): strong growth, but not as sharp as CA or FL.


## Insights

Smaller vacation or lifestyle towns (HI, FL, OR, CO) saw the highest percentage growth over 25 years.

Large metros (NY, LA, Chicago) grew in absolute price but not as explosively in relative terms.

Florida and California stand out as housing hotspots, reflecting population growth and demand.

The 2008 housing crash and COVID-19 housing boom are visible turning points in the data.


### Next Steps

Future improvements to this project could include:

Adding inflation adjustment for real vs nominal price growth

Incorporating income and affordability data

Forecasting housing trends using time series models (ARIMA, Prophet, LSTMs)

Mapping housing growth with geospatial visualizations

This project is for educational purposes. Data is sourced from Zillow.
