## Financial Data Analysis and Visualization
## Overview
This project performs financial data analysis and visualization using Python and Pandas. It extracts insights from various datasets, such as financial transactions, client information, payments, and subscription details. The analysis includes industry trends, subscription renewal rates, inflation impact, and payment trends over time.


## Features
- **Client Industry Analysis:** Determines the number of clients in different industries.
- **Subscription Renewal Insights:** Analyzes renewal rates across industries.
- **Inflation Impact on Renewals:** Maps inflation rates to renewal periods.
- **Payment Trends:** Identifies median payment trends over years.
- **Data Visualization:** Uses bar charts and pie charts to present insights.

## Data Sources
The project uses the following datasets:
- `finanical_information.csv` - Contains financial indicators such as inflation rates.
- `industry_client_details.csv` - Client information categorized by industry.
- `payment_information.csv` - Records of payments made by clients.
- `subscription_information.csv` - Subscription start and end dates, including renewal status.

## Requirements
To run this project, specific Python libraries must be installed, including Pandas, NumPy, and Matplotlib.

Usage Instructions
To execute this analysis:

Clone the repository from GitHub.

Navigate to the project directory.

Place the required CSV files in the designated data folder.

Run the Python script to perform the analysis.

## Visualizations
A bar chart displays the distribution of clients in different industries, such as Finance Lending and Blockchain.

A pie chart shows the subscription renewal rates for each industry.

Inflation rates during renewal periods are analyzed to determine their impact.

A bar chart illustrates median payments per year across all payment methods.

## Sample Output
Displays the number of clients in Finance Lending and Blockchain industries.

Highlights the industry with the highest subscription renewal rate.

Prints the average inflation rate during subscription renewal periods.

Presents the median amount paid per year using a bar chart.


# Financial Data Analysis and Visualization




## Requirements
To run this project, ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/financial-analysis.git
cd financial-analysis
```
2. Place the CSV files in the `Master Data/` directory.
3. Run the script:
```bash
python analysis.py
```

## Visualizations
- **Client Distribution:** Bar chart showing the number of clients in Finance Lending and Blockchain industries.
- **Renewal Rates:** Pie chart representing industry-wise subscription renewals.
- **Inflation Impact:** Computes the average inflation rate during renewals.
- **Payment Trends:** Bar chart showing median payments per year.

## Sample Output
- Number of Finance Lending clients: `XX`
- Number of Blockchain clients: `XX`
- Industry with highest renewal rate: `XYZ Industry`
- Average inflation rate during renewals: `X.XX%`
- Median payments per year: Displayed as a bar chart.

## License
This project is licensed under the MIT License.

## Author
Developed by **Arish Kumar P**

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.


