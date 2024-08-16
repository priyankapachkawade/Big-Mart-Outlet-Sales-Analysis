

This project focuses on performing an Exploratory Data Analysis (EDA) on BigMart's sales data. The dataset contains sales information for 1,559 products across 10 different stores in 2013. The goal of this analysis is to gain insights into the data and uncover underlying patterns that could help BigMart optimize its operations.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Summary](#analysis-summary)
- [Contributing](#contributing)

## Project Overview

BigMart has collected sales data across various outlets to understand the sales patterns and relationships between different variables. The analysis in this notebook includes:

- Loading and exploring the dataset.
- Analyzing the distribution of sales across different product categories and stores.
- Identifying key factors affecting sales.

## Dataset

The dataset used in this project is named `BigMart_sales.csv`, which contains 8,523 rows and 12 columns. Each row represents a product sold in a store, and each column provides information about the product or store.

### Features

- **Item Identifier**: Unique product ID
- **Item Weight**: Weight of the product
- **Item Fat Content**: Whether the product is low fat or regular
- **Item Visibility**: The visibility of the product in the store
- **Item Type**: Category to which the product belongs
- **Item MRP**: Maximum Retail Price (MRP) of the product
- **Outlet Identifier**: Unique store ID
- **Outlet Establishment Year**: The year the store was established
- **Outlet Size**: The size of the store (small, medium, large)
- **Outlet Location Type**: The type of city in which the store is located
- **Outlet Type**: Whether the outlet is a grocery store or a supermarket
- **Item Outlet Sales**: Sales of the product in the particular store

## Installation

To run this project locally, you need to have Python installed along with the following packages:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn
