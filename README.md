BNPL Credit Risk & Customer Behavior Analysis

A transaction-level credit risk analysis project designed to identify key default drivers and provide risk-based lending recommendations using Python and Power BI.

📌 Executive Summary

Buy Now Pay Later (BNPL) platforms face increasing default risk due to rapid digital approvals and minimal friction in lending.

This project analyzes 50,000 BNPL transactions to:

Identify high-risk customer segments

Evaluate transaction-level risk factors

Compare provider-level performance

Recommend actionable strategies to reduce portfolio loss

The goal is not just analysis — but business-focused decision support.

Business Problem

BNPL companies need to answer:

Who is most likely to default?

What transaction factors increase risk?

Which product categories generate high revenue but also high losses?

How can we reduce default without hurting growth?

This project approaches credit risk from a transaction intelligence perspective rather than only customer-level summary.

Dataset Description

50,000 synthetic BNPL transactions

Each row represents a single transaction

Target variable: Repayment_Status (Paid / Default)

Key Feature Categories:

Customer Demographics

Age

Income

Employment Status

Financial Risk Indicators

Credit Score

Purchase Amount

Transaction Context

Product Category

BNPL Provider

This structure allows risk to be analyzed at the granular transaction level.

Technology Stack
| Tool                   | Purpose                        |
| ---------------------- | ------------------------------ |
| Python (Pandas, NumPy) | Data cleaning & transformation |
| Matplotlib / Seaborn   | Exploratory data visualization |
| Power BI               | Business dashboard development |
| GitHub                 | Version control & portfolio    |

Analytical Approach
1️ Business Understanding

Defined core risk questions aligned with the lending strategy.

2️ Data Cleaning

Checked missing values

Standardized categorical variables

Removed inconsistencies

3️ Feature Engineering

Created business-friendly analytical features:

Credit Score Bands (Poor / Fair / Good / Excellent)

Income Groups (Low / Mid / High)

Purchase Amount Bands

Default Flag (Binary encoding)

4️ Exploratory Data Analysis (EDA)

Each visualization answered a specific business question.

5️ Dashboard Development

Built an interactive Power BI dashboard for stakeholder decision-making.

Key Insights

Credit Score is a Strong Default Predictor:
Lower credit score segments show significantly higher default probability.

High Purchase Amount = Higher Exposure Risk:
Larger transactions increase repayment burden and financial loss potential.

Category-Level Risk Trade-Off:
Some product categories generate strong revenue but also high default rates.

Income Alone is Not a Reliable Risk Filter:
Mid-income customers displayed unexpected default behavior patterns.

Provider-Level Variation Exists:
Different BNPL providers show differences in portfolio risk performance.

Power BI Dashboard Overview

The interactive dashboard includes:

Total Transactions & Default Rate KPIs

Credit Score vs Default Analysis

Product Category Risk Comparison

Provider-wise Risk Benchmarking

Income & Age Impact Analysis

Dynamic filtering by category and provider

This enables stakeholders to quickly identify high-risk segments.

Strategic Recommendations

Implement risk-based approval logic

Introduce dynamic credit limits based on credit score bands

Apply category-specific lending policies

Combine income and credit score for affordability modeling

Benchmark and optimize provider approval strategies

Business Impact:

This analysis provides a framework for:

Reducing portfolio default rate

Improving risk-adjusted profitability

Enhancing credit policy decisions

Supporting a data-driven lending strategy
