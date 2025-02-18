# Web Scraping and Data Mining for Alameda County Real Estate

## Table of Contents
- [Overview](#overview)
- [Data Source](#data-source)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
  - [Web Scraping](#web-scraping)
  - [Data Preprocessing](#data-preprocessing)
  - [Data Analysis](#data-analysis)
- [Research Questions](#research-questions)
- [Key Findings](#key-findings)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [Contact](#contact)

## Overview
This project leverages **web scraping and data mining** techniques to analyze real estate trends in **Alameda County, California**. The goal is to extract, preprocess, and analyze real estate data to uncover insights into property prices, trends, and neighborhood classifications.

## Data Source
- **MLS (Multiple Listing Service)**: A comprehensive platform for real estate listings.
- Web scraping was used to collect housing data including **price, square footage, property type, number of bedrooms and bathrooms, and HOA fees**.

## Tools & Technologies
- **Python** (BeautifulSoup)
- **Pandas, NumPy** for data processing
- **Matplotlib, Seaborn** for data visualization
- **Scikit-learn** for regression modeling and clustering

## Methodology
### Web Scraping
- Extracted property listings from MLS using Python's **Selenium** and **BeautifulSoup**.
- Collected details like price, property type, bedrooms, bathrooms, square footage, and HOA fees.

### Data Preprocessing
- Dropped rows with null values to improve data quality.
- Converted categorical and numerical data types for efficient analysis.
- Split **location** data into separate columns: Address, City, and Zip Code.
- Removed **price symbols** to enable numerical computations.

### Data Analysis
- Used **Linear Regression and Multiple Regression** to predict property prices based on square footage, bedrooms, and other features.
- Applied **clustering techniques** to identify housing market segments.

## Research Questions
- What property types are prevalent in Alameda County?
- What are the recent trends in selling prices across neighborhoods?
- How do factors like property type, size, and number of bedrooms/bathrooms affect pricing?
- What is the **average mortgage amount** in Alameda County?
- Can we predict house prices using **Linear Regression**?
- How can **clustering analysis** help identify unique neighborhood clusters?

## Key Findings
- **Top Cities by Listings**: 56% of homes are in **Pleasanton, Hayward, Fremont, and Oakland**.
- **Price Trends**:
  - 75% of homes are priced **below $2 million**, with a **minimum of $250K**.
  - **Piedmont** shows the greatest price fluctuations, while other cities have consistent pricing.
- **Regression Analysis**:
  - **Linear Regression** confirms that **square footage correlates with price**.
  - **Multiple Regression** shows that features like **bedrooms, bathrooms, and HOA fees impact pricing**.
- **Clustering Analysis** identified 4 key neighborhood types:
  - **Affordable Compact Homes**: Budget-friendly townhouses in Hayward, Union City, and Newark.
  - **Vintage Family Homes**: Older, premium homes in Berkeley, Livermore, and Oakland with low HOA fees.
  - **Balanced Borough**: Fremont offers a balance of affordability and comfort.
  - **Luxury Elite Homes**: Pleasanton leads in high-end, expensive homes with top-tier amenities.
<img width="640" alt="image" src="https://github.com/user-attachments/assets/ac0dab36-ce88-4bc8-943f-4976f76e2df1" />

## Future Enhancements
- Implement **automated web scraping** for real-time data updates.
- Explore **deep learning models** for better price prediction.
- Expand dataset to include **interest rates, crime rates, and school rankings**.
- Develop an **interactive dashboard** for real estate analytics.

## Contributors
- **Vinmathi Iyappan**
- **Priyanka Singh**
- **Shrikirti Vijayendra**
- **Pranjali Desai**
- **Garima Vijay**
- **Sri Tejaswi Kaparaboina**
- **Tia Cao**

## Contact
📧 **Email:** [vinmathi.iyappan@gmail.com](mailto:vinmathi.iyappan@gmail.com)  
🔗 **LinkedIn:** [Vinmathi-iyappan](https://linkedin.com/in//vinmathi-iyappan/)  
🖥 **GitHub:** [Vinmathiiyappan](https://github.com/Vinmathiiyappan)

