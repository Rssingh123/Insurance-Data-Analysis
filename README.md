# Insurance - Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/1d1e5ef5-778d-42c0-8619-48cfed1af7e7/c9f9356bbe587c9a7728?experience=power-bi

## Problem Statement
To identify the key issues in the insurance data problem statement, the following critical aspects should be considered:
 
1.) Claim Status Discrepancies: Several claims are marked as "Rejected" or remain "Pending," indicating potential inefficiencies or bottlenecks in claim processing. Understanding the reasons for these statuses could reveal issues in claim approvals or customer satisfaction.

2.) Demographic Influence:The dataset includes gender and age information. Analyzing how these demographics correlate with claim statuses or claim amounts may highlight biases or risk factors.

3.) Policy Type Variations:Different types of policies (Auto, Travel, Health, Life, Home) show varied claim patterns. Investigating claim acceptance rates and claim amounts by policy type can reveal which products have higher risks or operational challenges.

4.) Claim Amount and Premium Relationship:Disparities between premium amounts paid and claim amounts could indicate possible underwriting or pricing issues.

5.) Time-based Patterns:Policy start/end dates and claim dates can be analyzed for seasonal trends, delays, or policy utilization problems over time.

6.) Coverage vs. Claim Amount:Reviewing coverage amounts in relation to claim amounts could point out underinsured or overinsured segments.

### Steps followed

To load and prepare CSV data in Power BI, the key steps are as follows:

- Step 1: Import Data -> Open Power BI Desktop,Click on "Get Data" and select "Text/CSV."

- Step 2: Locate and select the CSV file to import.

- Step 3: Preview the data and click "Load" to bring it into Power BI.

- Step 4: Transform Data -> Use Power Query Editor to clean and shape the data.

- Step 5: Fix data types, e.g., date columns should be Date type, numeric columns should be decimal or whole number type.

- Step 6: Rename columns for clarity if needed.

- Step 7: Handle missing or null values by filling, removing, or replacing them,Remove duplicates if any.Split or merge columns if required for analysis.

- Step 8: Format date columns consistently (e.g., convert claim dates or policy dates to proper date format).

- Step 9: Create Measures and Calculated Columns:

- Step 10: Create derived columns or measures such as claim acceptance rates, total claims amount, or age groups from the age column.

- Step 11: Build Visualizations -> Use the cleaned and prepared data to build dashboards and reports, Filter by key attributes like claim status, policy type, or demographic groups.

- Step 12: Visualize trends over time using date columns like claim date or policy start/end date.

- Step 13 : Publish or Share
  Save and optionally publish the report to the Power BI Service. 

# Snapshot of Dashboard (Power BI Service)

## Insurance Dashboard P1
#### Power BI dashboard provides a comprehensive visual analysis of insurance data for PRISM INSURANCE PVT. LTD., covering key metrics and trends across policy types, claims, demographics, and policy activity.

Key Dashboard Elements
Header/Branding: Displays company name prominently.

Top Metrics: Yields quick summaries for Premium Amount (5.98M), Coverage Amount (600.55M), and Claim Amount (16.91M), providing an overview of business scale.

Filters: Users can filter by PolicyNumber, ClaimNumber, and CustomerID to drill down into specific details.

Demographic Breakdown
Gender split is shown: Female (5,001), Male (5,003), enabling demographic analysis.

Claims Analysis
Number of Claims By Status:

- Rejected: 4.4K

- Settled: 3.4K

- Pending: 2.3K

Claim Amount by Age Group:

- Adult: 8.8M

- Elder: 6.4M

- Young Adult: 1.7M

Identifies which age groups drive higher claim costs.

Premium Distribution Premium Amount by Policy Type:

- Health: 2.5M

- Travel: 1.2M

- Auto: 1.0M

- Life: 0.7M

- Home: 0.6M

Enables comparison of product profitability.

Activity Analysis
Count of Active/Inactive Policies:

- Active: 4,190 (41.87%)

- Inactive: 5,826 (58.13%)

- Pie chart visualizes policy engagement and retention.

Detailed Claims Table:- Shows policy type-level split by claim status (Pending, Rejected, Settled), with specific amounts for each. This is critical for monitoring health of different products across claim cycles.

![Snap_1](https://github.com/Rssingh123/Insurance-Data-Analysis/blob/6ee9401a13de97e6e658b60b28054f01e7adb6a0/Insurance%20P1.png)

## Insurance Dashboard P2  
#### Table presents detailed insurance policy records for individual customers, capturing essential policy and customer attributes. Each row represents a single policy and includes the following fields:

- ClaimNumber: Unique identifier for each claim.

- CustomerID: Unique identifier for each customer.

- PolicyNumber: Specific policy associated with the customer.

- Gender: Indicates if the customer is Male or Female.

- Age: Age of the insured customer.

- CoverageAmount: The total coverage provided by the policy (the insured sum).

- PremiumAmount: The amount paid by the customer as a premium for the policy.

- PolicyStartDate: The start date of the policy's validity.

- PolicyEndDate: The end date of the policy's validity.

- PolicyType: The type of insurance policy (Auto, Travel, Health, Life, Home).

      
![Snap_2](https://github.com/Rssingh123/Insurance-Data-Analysis/blob/6ee9401a13de97e6e658b60b28054f01e7adb6a0/Insurance%20P2.png)

## Insurance Customer Feedback Dashboard P3
#### Dashboard presents a detailed analysis of customer feedback and sentiment regarding insurance services. It is structured into three main visual elements:

1. Word Cloud (Left Table)
Purpose: Provides a visual summary of the most commonly used words in customer feedback.

Highlights: Prominent words include "service," "policy," "very," "satisfied," "claims," "process," and "helpful."

Helps quickly identify key themes and common topics mentioned by customers, such as satisfaction with service, coverage options, claims process, and issues with the website or billing.

2. Feedback Sentiment Table (Top Right Table)
Purpose: Lists individual customer comments along with quantitative sentiment scores.

Contents:Customer Name

Score Sentiment: Ranging from near 0 (negative) to almost 1 (positive).

Feedback: Written comments detailing experiences, both positive ("Great coverage options, very happy") and negative ("Website was down, inconvenient").

Insights: Easy identification of happy customers as well as pain points (e.g., high premiums, confusing policies, billing issues).

3. Feedback Category Bar Chart (Bottom Right Table)
Purpose: Summarizes feedback by category for quantitative evaluation.

Categories:

- Excellent (54 customers)

- Needs Improvement (39 customers)

- Good (4 customers)

Insights:

- Most feedback falls under "Excellent," suggesting overall positive experiences.

- A substantial segment ("Needs Improvement") points to opportunities for process, communication, or service enhancement.

![Snap_3](https://github.com/Rssingh123/Insurance-Data-Analysis/blob/6ee9401a13de97e6e658b60b28054f01e7adb6a0/Insurance%20P3.png)
