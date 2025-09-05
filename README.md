# Analysis-of-Myntra-Apparel

## Project Overview

This project analyzes Myntra apparel product data using **Excel functions** for **data cleaning, preparation, analysis, and retrieval**.
The goal is to gain insights into product pricing, discount strategies, and customer preferences.

---

##  Key Steps

### 1. **Data Cleaning & Preparation**

* Removed duplicate values.
* Standardized the **DiscountOffer** column into a uniform format.
* Filled missing **DiscountPrice** values with the category-wise average.
* Replaced null values in **SizeOption** with `"Not Available"`.

### 2. **Data Analysis**

* Calculated the **average original price** for products with ratings above 4.
* Counted the number of products with **discounts greater than 50%**.
* Counted the number of products available in **Size M**.
* Created a new column to label offers as:

  * **High Discount** → more than 50%
  * **Low Discount** → 50% or below

### 3. **Data Retrieval & Lookup**

* Used **VLOOKUP/XLOOKUP** to fetch brand, price, and rating for a given product ID.
* Applied **INDEX & MATCH** to find the discount price of specific products.

---

##  Files in this Repository

* `Analysis of Myntra Apparel.pdf` → Project report & documentation.
* Dataset(https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view)

---

##  Tools & Techniques Used

* **Excel Functions**: Remove Duplicates, IF, COUNTIFS, VLOOKUP, XLOOKUP, INDEX-MATCH.
* **Data Cleaning**: Standardization, null handling, error removal.
* **Data Analysis**: Pricing insights, discount categorization.

---

## Key Insights

* Products with **ratings > 4** tend to have a higher average original price.
* A significant number of items have discounts **greater than 50%**, making Myntra a highly **discount-driven platform**.
* Size **M** is one of the most commonly available sizes across products.

---

## Author

 **Disha Sindhi**

* 📧 Email: [dishasindhi7@gmail.com](mailto:dishasindhi7@gmail.com)
* 🔗 [LinkedIn](https://www.linkedin.com/in/disha-sindhi-b0092732a/)
* 📂 [Portfolio](https://www.wscubetech.com/portfolio/data/disha-sindhi-rsk7ymi)
* 💻 [GitHub](https://github.com/DishaSindhi)

---

 *This project demonstrates how Excel can be used for data analytics in e-commerce, focusing on Myntra’s apparel dataset.*
