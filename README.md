# A Comparative Study of Smartphones Available in 2024

![Smartphone Banner](phone_image2.webp)

## Overview

This notebook presents an in-depth analysis of the smartphones available in 2024. Using data from GSMArena, one of the most popular sources for smartphone specifications and reviews, the analysis focuses on phones that are still listed for sale. This helps us identify trends in the current smartphone market and offer insights into which models provide the best value for consumers.

## Table of Contents

1. [Importing Libraries](#1)
2. [About Dataset](#2)
3. [Basic Exploration and Cleaning](#3)
4. [Grouping Listings from E-commerce](#4)
5. [Dataset Summary](#5)
6. [Price Distribution](#6)
7. [Correlations](#6)
8. [Most Common Configs](#6)
9. [Displays](#6)
10. [Final Thoughts](#6)

## Dataset

The dataset used in this analysis includes information on smartphone brands, models, prices, and detailed technical specifications, all sourced from GSMArena. It contains two primary sections:

- **phone_brand:** Manufacturer or brand (e.g., Apple, Samsung, Xiaomi)
- **phone_model:** Specific model name or number
- **price:** Price point of the phone (exact or estimated)
- **specs:** Dictionary of detailed technical specifications (screen size, camera, processor, battery life, etc.)
- **pricing:** Dictionary of price listings across different e-commerce websites

Older models and discontinued listings have been excluded to focus on phones currently available for sale.

## Key Steps in the Analysis

1. **Data Cleaning:** 
    - Handling missing values and cleaning the price data.
    - Structuring the dictionary-based specifications for easier access and manipulation.
    
2. **Exploration of Features:**
    - Analyzing key phone features such as screen size, camera specifications, processor type, and battery life.
    
3. **Price vs Specifications Analysis:**
    - Correlating technical specifications with the price to uncover any relationships or trends.
    - Identifying models that provide the best value in terms of their price-to-specifications ratio.
    
## Requirements

To install the necessary dependencies, you can use:

```bash
pip install -r requirements.txt
```
or
```bash
pip install --upgrade -r requirements.txt
```
## Usage
1. **Clone the repository:**
```bash
git clone https://github.com/KhalSCI/A-Study-of-Smartphones-Available-in-2024.git
```
2. **Open the Jupyter Notebook**
```bash
jupyter notebook analysis.ipynb
```
## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Authors

- [Khal](https://github.com/KhalSCI)