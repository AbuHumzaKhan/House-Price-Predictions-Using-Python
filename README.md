
# House Sales in King County, USA

## 📌 Project Overview

This project analyzes house sales data in King County, USA (including Seattle) for homes sold between May 2014 and May 2015. The goal is to explore relationships between different house features and sale prices, perform data cleaning, exploratory data analysis (EDA), and build predictive models to estimate house prices.

---

## 📂 Dataset Details

The dataset contains information on house sales with the following key variables:

| Variable       | Description                                                   |
| -------------- | ------------------------------------------------------------- |
| id             | Unique ID for each house sale                                 |
| date           | Date house was sold                                           |
| price          | Sale price (Target variable)                                  |
| bedrooms       | Number of bedrooms                                            |
| bathrooms      | Number of bathrooms                                           |
| sqft\_living   | Square footage of living space                                |
| sqft\_lot      | Square footage of lot size                                    |
| floors         | Number of floors                                              |
| waterfront     | Indicates if the house is near a waterfront (1 = Yes, 0 = No) |
| view           | Quality of the view                                           |
| condition      | Overall condition rating                                      |
| grade          | Overall grade based on King County grading system             |
| sqft\_above    | Square footage above ground                                   |
| sqft\_basement | Square footage of basement                                    |
| yr\_built      | Year the house was built                                      |
| yr\_renovated  | Year of last renovation                                       |
| zipcode        | Zip code location                                             |
| lat, long      | Latitude & Longitude coordinates                              |
| sqft\_living15 | Living space in 2015 (post-renovation)                        |
| sqft\_lot15    | Lot size in 2015 (post-renovation)                            |

---

## 🛠️ Setup Instructions

1. Install required dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open the notebook:

   ```bash
   jupyter notebook House_Sales_in_King_Count_USA.ipynb
   ```
3. Run all cells sequentially to perform data analysis.

---

## 📊 Analysis Workflow

1. **Data Loading & Cleaning**

   * Handling missing values
   * Converting data types
   * Removing outliers

2. **Exploratory Data Analysis (EDA)**

   * Summary statistics
   * Correlation analysis
   * Distribution plots & boxplots

3. **Feature Engineering**

   * Creating new features if required
   * Encoding categorical variables

4. **Modeling**

   * Applying regression models
   * Evaluating model performance

5. **Visualization**

   * Heatmaps
   * Scatter plots
   * Price vs. Feature analysis

---

## 📈 Key Insights

* Relationship between square footage and price
* Impact of location (zipcode, waterfront) on pricing
* Effect of renovation year on house prices
* Model accuracy for price prediction

---

## 🚀 Future Enhancements

* Implement advanced machine learning models (e.g., Random Forest, XGBoost)
* Deploy the model using Flask/Django for real-time predictions
* Create an interactive dashboard using Power BI/Tableau

---

## 🧑‍💻 Author

* **Project by:** Abu Humza Khan
* **Tools Used:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn
