# Analyzing Marketing Campaigns

This repository contains code and data for analyzing marketing campaigns. The analysis focuses on evaluating the effectiveness of different marketing strategies through various statistical methods, including A/B testing.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we analyze marketing campaign data to understand the impact of different marketing channels and strategies on user conversion rates. The goal is to identify the most effective tactics to maximize conversions and optimize marketing spend.

## Data

The dataset used in this analysis contains information on marketing campaigns, including user interactions, conversion status, and campaign variants. The data includes the following columns:

- `user_id`: Identifier for each user.
- `date_served`: Date when the marketing message was served.
- `marketing_channel`: Channel through which the marketing message was delivered.
- `variant`: A/B test variant (e.g., "personalization").
- `converted`: Whether the user converted (True/False).
- `language_displayed`: Language in which the marketing message was displayed.
- `language_preferred`: User's preferred language.
- `age_group`: Age group of the user.
- `date_subscribed`: Date when the user subscribed.
- `date_canceled`: Date when the user canceled the subscription (if applicable).
- `subscribing_channel`: Channel through which the user subscribed.
- `is_retained`: Whether the user is retained (True/False).

## Analysis

The analysis involves the following steps:

1. **Data Cleaning**: Removing NaN values and preparing the data for analysis.
2. **Descriptive Statistics**: Summarizing the data to understand basic trends and patterns.
3. **A/B Testing**: Conducting t-tests to compare conversion rates between different variants.
4. **Visualization**: Creating visualizations to illustrate the findings.

## Results

The results of the analysis are presented in the form of statistical outputs and visualizations. Key findings include:

- The personalized marketing campaign variant significantly outperformed the control variant in terms of conversion rates.
- Optimizing marketing channels led to a substantial reduction in customer acquisition costs.

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/veeravallisarathkumar/Analyzing-Marketing-Campaigns.git
