# Airbnb Exploratory Data Analysis | Python

## 🧭 Project Overview

Airbnb is a global online marketplace that connects travelers with hosts offering different types of accommodations. With listings ranging from private rooms to entire homes and apartments, Airbnb provides travelers with a wide variety of accommodation choices.

This project performs an **Exploratory Data Analysis (EDA)** on Airbnb listing data to understand pricing patterns, customer preferences, neighborhood characteristics, host activity, reviews, and listing availability.

The analysis uses Python-based data analysis and visualization techniques to identify meaningful patterns and generate business-oriented insights from the dataset.

---

## 🎯 Project Objectives

The primary objectives of this project are to:

* Understand the distribution of Airbnb listings across different locations.
* Analyze how prices vary across neighborhoods and room types.
* Identify the most common and preferred room types.
* Explore the relationship between price, reviews, and listing popularity.
* Analyze host activity and its impact on listings.
* Examine listing availability throughout the year.
* Identify important patterns and trends that can support business decisions.

---

## 📊 Dataset Description

The dataset contains information about Airbnb listings, including:

### Listing Information

* Listing ID
* Listing name
* Host ID
* Host name
* Neighborhood group
* Neighborhood
* Latitude
* Longitude

### Accommodation Information

* Room type
* Price
* Minimum nights

### Review Information

* Number of reviews
* Last review date
* Reviews per month

### Host Information

* Number of listings managed by the host

### Availability Information

* Number of days the listing is available during the year

These attributes allow different aspects of the Airbnb marketplace to be explored through statistical analysis and visualization.

---

## 🧹 Data Cleaning & Preparation

Before performing the analysis, the dataset was inspected and prepared to improve data quality.

The preprocessing included:

* Checking the dataset structure and data types.
* Identifying missing values.
* Handling missing and inconsistent data.
* Checking for duplicate records.
* Examining numerical variables for unusual values and outliers.
* Converting date-related columns into appropriate formats.
* Preparing categorical and numerical variables for analysis.

---

## 🔍 Exploratory Data Analysis

The project explores several important aspects of Airbnb listings.

### 1. Price Analysis

Analyzed Airbnb prices to understand:

* Overall price distribution.
* Average price across neighborhood groups.
* Price differences between room types.
* Price variation across individual neighborhoods.
* Presence of unusually high-priced listings.

### 2. Neighborhood Analysis

Examined listing distribution across different neighborhoods to identify:

* Areas with the highest number of listings.
* Areas with higher and lower average prices.
* Neighborhoods with greater customer activity.
* Geographic patterns in Airbnb listings.

### 3. Room Type Analysis

Analyzed the distribution of available room types to determine:

* The most common room type.
* Customer preference across accommodation types.
* Price differences between entire homes, private rooms, and other room categories.
* Availability patterns across different room types.

### 4. Reviews & Listing Popularity

Explored review-related variables to understand:

* Which listings receive more reviews.
* The relationship between price and number of reviews.
* Neighborhoods with higher review activity.
* Patterns that may indicate listing popularity.

### 5. Availability Analysis

Analyzed the number of days listings are available throughout the year to understand:

* Highly available listings.
* Areas with lower availability.
* Differences in availability between room types.
* Possible relationships between price and availability.

### 6. Host Activity Analysis

Investigated host-level information to understand:

* Hosts managing multiple listings.
* Distribution of listings among hosts.
* Relationship between host activity and listing availability.
* Differences between individual and multi-listing hosts.

---

## 📈 Visualization Techniques

Several visualization techniques were used to identify patterns and communicate findings effectively.

* Bar charts
* Histograms
* Box plots
* Scatter plots
* Line charts
* Heatmaps
* Pie/Donut charts
* Geographic visualizations
* Correlation analysis

These visualizations make it easier to compare categories, identify trends, detect outliers, and understand relationships between variables.

---

## 💡 Key Business Insights

The analysis provides insights that can be useful for different stakeholders in the Airbnb marketplace.

### For Hosts

* Pricing can be adjusted according to neighborhood and room type.
* Understanding local competition can help hosts develop better pricing strategies.
* Review activity can provide an indication of listing popularity.
* Availability patterns can help hosts optimize their booking calendars.

### For Travelers

* Comparing neighborhoods can help travelers identify suitable locations within their budget.
* Room-type analysis provides an overview of available accommodation options.
* Price and review information can help travelers make better booking decisions.

### For Business Stakeholders

* Neighborhood-level analysis can help identify high-demand markets.
* Room-type distribution provides insights into customer preferences.
* Host activity helps understand the supply side of the marketplace.
* Pricing and availability patterns can support marketplace and operational decisions.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🚀 Conclusion

This Airbnb EDA project demonstrates how Python can be used to transform raw marketplace data into meaningful insights.

Through data cleaning, exploratory analysis, statistical techniques, and visualization, the project investigates **pricing, neighborhoods, room types, reviews, availability, and host activity**.

The analysis provides a better understanding of Airbnb's marketplace dynamics and demonstrates practical **data analysis and business intelligence skills** that can be applied to real-world datasets.
