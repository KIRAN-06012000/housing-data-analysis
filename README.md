# 🏡 Housing Data Analysis Project

This project analyzes a housing dataset to uncover factors influencing property prices. It covers data cleaning, categorical encoding, exploratory data analysis (EDA), feature engineering, visualizations, and insights — all done in a single Jupyter Notebook: `KIRANPYTHON.ipynb`.

---

## 📝 Dataset Description

| Column           | Description                                      |
|------------------|--------------------------------------------------|
| `date`           | Date when property info was recorded             |
| `price`          | Sale price of the property                       |
| `bedrooms`       | Number of bedrooms                               |
| `bathrooms`      | Number of bathrooms                              |
| `sqft_living`    | Living area in square feet                       |
| `sqft_lot`       | Lot size in square feet                          |
| `floors`         | Number of floors                                 |
| `waterfront`     | 1 if the house has a waterfront, else 0          |
| `view`           | View quality index (0–4)                         |
| `condition`      | Property condition (rating 1–5)                  |
| `sqft_above`     | Above-ground living area                         |
| `sqft_basement`  | Basement area                                    |
| `yr_built`       | Year built                                       |
| `yr_renovated`   | Year last renovated                              |
| `street`         | Street address                                   |
| `city`           | City                                             |
| `statezip`       | State and ZIP code                               |
| `country`        | Country                                          |

---

## 🚀 How to Run This Project on JupyterHub

1. **Log in to JupyterHub**  
   Open your JupyterHub URL (e.g., `https://yourhub.com`) and log in with your credentials.

2. **Upload Files**  
   Upload the following:
   - `code/KIRANPYTHON.ipynb`
   - `data/housing.xlsx`
   - `requirements.txt`

3. **(Optional) Install Required Packages**  
   Open a Terminal in JupyterHub and run:

pip install --user -r requirements.txt


4. **Run the Notebook**  
- Navigate to the `code/` folder  
- Open `KIRANPYTHON.ipynb`  
- Click `Kernel > Restart & Run All` to execute the notebook from top to bottom

---

## ⚙️ Python Requirements

Add these to `requirements.txt`:

pandas
numpy
matplotlib
seaborn
scikit-learn
openpyxl
jupyterlab
notebook

Then install with:

pip install --user -r requirements.txt

---

## 📊 Analysis Highlights

- **Data Cleaning**: Missing values, duplicates, type conversions
- **Categorical Encoding**: Label and one-hot encoding
- **EDA**: Distributions, relationships, correlations
- **Feature Engineering**:
  - `price_per_sqft`: `price / sqft_living`
  - `property_age`: `2025 - yr_built`
  - `is_renovated`: `1 if yr_renovated > 0 else 0`
- **Visualizations**:
  - Histograms, box plots, scatter plots
  - Correlation heatmaps, bar plots

---

## 📈 Key Insights

- 🏙️ Location plays a major role in price variability
- 🏞️ Waterfront and view properties command premium prices
- 🚿 Bathrooms have more pricing impact than bedrooms
- 🏡 Renovated homes tend to sell at higher prices
- 📏 Larger homes (higher `sqft_living`) = higher value

---

## 👨‍💻 Author

**KIRAN M**  
📧 kiranklgd2000@gmail.com  
🔗 [https://github.com/KIRAN-06012000]

---

## 🙌 Acknowledgements

- Dataset structure inspired by real estate industry practices  
- Visualizations powered by Matplotlib and Seaborn  
- JupyterHub used as the computing environment