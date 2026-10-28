# Loan Default Risk Dashboard | Power BI

## Project Overview
The Loan Default Risk Dashboard is a Power BI project designed to analyze historical loan default patterns and identify customer segments that may require closer credit-risk review.

The dashboard explores loan applications across income groups, employment types, loan purposes, and credit-related indicators. It also demonstrates a rule-based approach to flagging applications for manual review.

## Business Problem
Financial institutions need to understand historical loan default patterns to support portfolio monitoring and prioritize applications for further review.

This project addresses two questions:
1. Which customer segments have higher observed loan default rates?
2. How can applications be flagged for manual review using transparent, rule-based criteria?

## Objectives
- Monitor total loan applications and historical default rate.
- Compare default rates across income groups, employment types, and loan purposes.
- Explore credit score and debt-to-income ratio (DTI) patterns.
- Demonstrate rule-based risk categorization and manual-review flags.
- Present findings through an interactive Power BI dashboard.

## Tools & Technologies
- Microsoft Power BI Desktop
- Power Query for data preparation, where applicable
- DAX for measures and calculated columns
- GitHub for project documentation and versioned portfolio assets

## Dashboard Pages
### 1. Loan Risk Overview
- Total loan applications
- Historical default rate
- Average income
- Average loan amount
- Average credit score
- Default distribution and segment-level comparisons
- Interactive slicers for customer and loan characteristics

### 2. Default Probability Analysis
Planned/implemented analysis of historical default rates across income, loan purpose, employment, credit-score groups, DTI groups, and co-signer status. See the report screenshots for the visuals completed.

### 3. Risk Scoring & Manual Review
A rule-based demonstration that categorizes applications using credit score and DTI criteria and flags selected records for manual review. The rules are illustrative and require validation before any real lending use.

## Key DAX Measures
- Total Applications
- Defaulted Applications
- Default Rate %
- Average Income
- Average Loan Amount
- Average Credit Score

The default rate is calculated from the observed default indicator and the number of loan applications. Results should be interpreted as historical rates, not predicted future probabilities.

## Methodology
1. Load the loan dataset into Power BI.
2. Review fields and data types.
3. Create DAX measures for portfolio-level KPIs.
4. Group income, credit scores, and DTI values for segment comparisons.
5. Build interactive visuals and slicers.
6. Demonstrate rule-based risk categorization and review flags.
7. Validate calculations and document findings.

## Business Value
The dashboard helps users explore historical default patterns, compare customer segments, monitor portfolio metrics, and demonstrate how transparent screening rules can support a manual-review workflow.

## Limitations
- Observed default rates do not establish causation.
- This dashboard does not independently predict future loan defaults.
- Risk categories are illustrative rules, not a validated credit-scoring model.
- Geographic analysis is not included unless a suitable geography field is available.
- Actual findings and threshold choices should be validated against the dataset before drawing business conclusions.

## Author
Kanishka Singh

Data Analytics Portfolio Project | Power BI
