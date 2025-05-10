# Flipkart Laptop Reviews – Data Analysis Project

## 📌 Project Overview
This repository presents a data analysis project based on a dataset of laptop reviews from Flipkart. It is developed as part of **Task 1** for the **Decision Support Systems (DSS)** module in the Postgraduate Diploma in Artificial Intelligence at IDEA College, Mosta, Malta.

The goal of the project is to explore customer feedback and uncover patterns that reveal what factors influence positive or negative laptop reviews. The analysis uses visual techniques and is contextualised within the scope of decision support systems in real-world business applications.

## 🔗 Dataset Source
**Dataset:** [Flipkart Laptop Reviews – Kaggle](https://www.kaggle.com/datasets/gitadityamaddali/flipkart-laptop-reviews)  
The dataset contains over 24,000 customer reviews covering approximately 600 laptop models. Each entry includes ratings, review titles, and full review content.

**Features:**
- `product_name` – Laptop model and specs  
- `overall_rating` – Average rating per product  
- `no_ratings` – Total number of user ratings  
- `no_reviews` – Total number of user reviews  
- `rating` – Individual review score  
- `title` – Short review title  
- `review` – Full written review

## 📊 Key Components
- Data loading and UTF-8 encoding validation  
- Data cleaning (duplicate removal, numeric conversions)  
- Exploratory data analysis (EDA) using Python  
- Visualizations with `matplotlib` and `seaborn`  
- Charts showing:
  - Rating distribution (with percentage labels)
  - Most reviewed laptops
  - Top-rated laptops
  - Review count vs. rating (scatter)
  - Review length vs. rating (box plot)
- Theoretical discussion connecting results to DSS concepts

- The findings are tied to the application of decision support systems in business environments and demonstrate how data analysis supports informed decision-making.

## 📁 Project Structure
- `Flipkart_Laptop_Review_EDA.ipynb` – Main Jupyter notebook  
- `laptops_dataset_final_600.csv` - The data set
- `Visual Analysis/` – Folder containing all saved visual outputs  
- `reference.md` – Harvard-style citation list of all libraries, tools, and academic references  
- `requirements.txt` – Python dependencies used in this notebook

---

