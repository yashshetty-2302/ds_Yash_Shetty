# ds_Yash_Shetty: Trading Behavior and Market Sentiment Analysis

## Project Objective
This project performs an Exploratory Data Analysis (EDA) to analyze the complex relationship between individual trader behavior and overall market sentiment (Fear vs. Greed). The primary goal is to:

1.  Analyze how key trading metrics (profitability, risk, volume, leverage) align or diverge from market sentiment across various phases of the market cycle.
2.  Identify hidden trends and actionable signals that can be used to develop smarter, non-emotional trading strategies.

## Strategic Analysis: Key Findings

The analysis reveals a **strong divergence** between emotional sentiment and successful trading. The most effective strategies involve acting *contrary* to the crowd's emotional state.

| Finding Category | Alignment/Divergence | Strategic Takeaway |
| :--- | :--- | :--- |
| **Directional Edge** | **Strong Divergence** | **Selling/Shorting** trades consistently have a **Win Rate nearly double** that of Buying/Longing trades. |
| **Risk/Timing** | **Strong Divergence** | The **largest, riskiest trades** are placed during **Fear**, but this risk is wasted as it yields no higher median returns. |
| **Profit Maximization** | **Alignment** | Highest PnL is achieved during **Extreme Greed**, but often by scaling up **SOL** longs, or by aggressively **shorting** (best Win Rate). |
| **Cost Efficiency** | **Divergence** | Execution is **cheapest** (lowest fees) during **Extreme Greed** and most expensive during **Fear**. |

##  Setup Instructions

To run this project and reproduce the analysis locally, please follow the steps below.

### Prerequisites

* Python 3.8+ (Recommended)
* `pip` (Python package installer)

### Step 1: Clone the Repository

Navigate to the directory where you want to store the project and clone the repository.

```bash
git clone [https://github.com/yashshetty-2302/ds_Yash_Shetty.git](https://github.com/yashshetty-2302/ds_Yash_Shetty.git)
cd ds_Yash_Shetty/ds_Yash_Shetty
