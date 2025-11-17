# **S – Situation**

Airbnb listings in New York City vary widely in price, availability, and host behavior. The dataset was messy, lacked important analytical columns, and offered no direct visibility into factors that drive listing prices, demand, or host performance.
My objective was to clean the data, engineer meaningful features, perform EDA, and visualize key business insights that explain what drives price variation and how host-level and location-level patterns differ.

# **T – Task**

My responsibilities were:

Clean and structure the dataset so that it could support accurate analysis.

Engineer new variables (e.g., host experience, superhost logic, availability buckets).

Identify the major factors influencing pricing, demand, and review behavior.

Build clear and visually intuitive charts that highlight neighborhood trends, room-type dynamics, and host-level patterns.

Deliver insights that would be valuable to stakeholders (hosts, customers, and platform).

# **A – Action**
**1. Data Cleaning & Feature Engineering**

Removed duplicates and handled missing data.

Created new columns such as:

Host experience in years

Superhost classification

Has_reviews flag

Availability buckets

Standardized inconsistent text fields and corrected skewed columns.

These changes significantly improved usability of the dataset and enabled deeper analysis.

**2. Exploratory Data Analysis (EDA)**

I investigated the question: “What factors influence Airbnb pricing and demand in NYC?”

Key analytical actions:

Analyzed price distribution across all boroughs.

Explored room-type impact on price and availability.

Examined how host characteristics affect listing performance.

Identified patterns in review frequency and guest behavior.

**3. Visualization & Insights**

Using matplotlib and seaborn visualizations:

Major Findings:

Pricing:

99.4% of listings are priced below $1000, with luxury outliers concentrated largely in Manhattan.

Manhattan and Brooklyn dominate high-price listings; Bronx and Staten Island remain the most affordable.

Room Type Influence:

Entire homes/apartments have the highest prices and lowest availability.

Shared rooms are the cheapest and most available, indicating lower demand.

Neighborhood Dynamics:

Manhattan neighborhoods cluster into high-price zones driven by tourism and premium inventory.

Staten Island sees lower prices but higher availability due to lower tourist traffic.

Review Patterns:

Review frequency is significantly lower in Manhattan, suggesting high occupancy or less review-active guests.

Higher availability correlates with fewer reviews, implying lower demand.

Host-Level Insights:

Superhosts maintain more competitive prices, likely due to optimized demand strategies.

New hosts tend to price lower to attract initial bookings.

These insights collectively answer what drives price variation—primarily location, room type, and host reputation.

# **R – Result**

Through cleaning, EDA, and visualization, I produced a structured analytical story explaining Airbnb dynamics in NYC:

Identified the top 3 drivers of price:
Location → Room Type → Host Experience

Revealed supply–demand gaps using availability and pricing data.

Provided actionable insights for:

Hosts → how to price competitively

Guests → where to find low-cost stays

Airbnb → which boroughs need host expansion or pricing guidance

Delivered a fully reproducible analysis pipeline in Python, with clean notebooks for each phase (Cleaning → EDA → Viz).

This project strengthened my end-to-end analytical workflow:
data cleaning → feature engineering → analysis → visualization → business storytelling.
