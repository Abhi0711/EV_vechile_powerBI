# Electric Vehicle (EV) Market Dashboard & Analysis

This project analyzes the electric vehicle market landscape to uncover regional adoption trends, manufacturer performance, cost efficiencies, and the impact of government policies. The analysis is structured across two distinct Excel workbooks—categorized into **Basic** and **Medium** level problem statements—and culminating in a dynamic Power BI dashboard.

## Project Requirements

* **Data Inputs:** The dataset encompasses state names, manufacturer details, sales volumes, penetration rates, vehicle categories (2-wheelers vs. 4-wheelers), running costs, and government subsidy types.


* **Analytical Structure:** The workflow requires two separate Excel files to isolate Basic factual queries from Medium-level analytical challenges involving growth rates and seasonality.
* **Output:** An interactive dashboard providing insights to manufacturers, policymakers, and consumers regarding market shifts and infrastructure needs.



## Tools and Techniques

* **Microsoft Excel / CSV:** Utilized as the primary data storage and processing tool to structure the Basic and Medium-level problem sets before visualization.


* **Power BI Desktop:** Employed to create combo charts, clustered bar/column charts, line charts, and filled maps for geographical subsidy visualization.


* **Power Query Editor:** Used for data transformation tasks such as reshaping vehicle category columns, cleaning data, and ensuring accurate numeric formatting for penetration rates.


* **Data Analysis Expressions (DAX):** Applied to calculate the Compound Annual Growth Rate (CAGR) for both states and EV makers over specified time periods.



## Challenges Faced

* **Data Aggregation and Reshaping:** Sales figures for different vehicle types (2-wheelers vs. 4-wheelers) and timeframes required careful aggregation and reshaping to enable accurate side-by-side or proportional comparisons.


* **Complex Metric Calculation:** Calculating accurate CAGR required establishing custom measures using initial and final sales values across multiple years.


* **Categorizing Policies:** Mapping diverse state-wise government incentives (e.g., tax rebates versus charging infrastructure support) into uniform, analyzable categories presented a significant data cleaning hurdle.



## Analytical Insights

### Basic Level Insights (Sales, Makers, and Costs)

* **Overall Market Volume:** The total vehicle market recorded 57M sales, with EVs accounting for 2M units, resulting in a national EV penetration rate of 3.61%.


* **Top Manufacturers by Sales:** Tata Motors leads the market by a significant margin, followed by Mahindra & Mahindra, MG Motor, BYD India, and Hyundai Motor.


* **Cost Efficiency:** EVs offer drastic long-term savings, with an annual running cost of ₹29,200 (₹1.60/km), compared to ₹120,906.25 (₹6.63/km) for petrol and ₹112,953.13 (₹6.18/km) for diesel vehicles.


* **Vehicle Categories:** While 2-wheelers often act as an affordable entry point for urban consumers, targeted sample data highlights periods where 4-wheelers can account for up to 75% of proportional category sales.



### Medium Level Insights (Growth, Seasonality, and Penetration)

* **Leading States by Penetration:** Karnataka, Maharashtra, Rajasthan, and Gujarat demonstrate the highest penetration rates, indicating that a larger percentage of total vehicle sales in these regions are electric.


* **Fastest Growing Markets (CAGR by State):** Emerging markets such as Meghalaya, Tripura, Nagaland, Chandigarh, and Chhattisgarh display the highest Compound Annual Growth Rates, highlighting rapidly accelerating local adoption.


* **Fastest Growing Makers (CAGR by Maker):** BMW India leads maker growth metrics, followed by Volvo Auto India, BYD India, and Hyundai Motor. The total maker CAGR across the board sits at an impressive 93.91%.


* **Seasonal Sales Cycles:** EV sales exhibit strong seasonality, with an absolute peak in March (approaching 0.3M sales) and subsequent surges toward the end of the year (November and December) driven by festive seasons and year-end promotions.


* **Impact of Government Policies:** State-wise variations in subsidies—ranging from tax exemptions to charging infrastructure support—heavily influence regional adoption speeds and help manufacturers align their supply chains with local governmental priorities.
