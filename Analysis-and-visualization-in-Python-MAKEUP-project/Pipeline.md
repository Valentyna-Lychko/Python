## Pipeline (Project Workflow)

### **1. makeup_api_loading.ipynb**
- Loading data from the [Makeup API](https://makeup-api.herokuapp.com/api/v1/products.json).
- Saving data to a JSON file: `makeup_all_products.json`.

---

### **2. makeup_research_dataset.ipynb**
- Importing data from `makeup_all_products.json`.
- Initial analysis of structure, content, and properties of the data.

---

### **3. makeup_data_preparation.ipynb**
- Loading and preparing data for analysis.
- Splitting into separate datasets:
  - **`makeup_valid_prices.csv`**
  - **`makeup_no_prices.csv`**
  - **`makeup_additional_info.csv`**
- Filling missing values in key columns.
- Adding new columns:
  - `categorize_price`, `brand_popularity`, `category_product_type`.

---

### **4. makeup_color_table.ipynb**
- Creating a color palette.
- A color table for visual analytical charts.

---

### **5. makeup_project_visualization.ipynb**
#### Chart Building:
1. **Number of unique product names, brands, categories, and types.**  
2. **Number of brands and products by category-product type combinations.**  
3. **Number of items by price category.**  
4. **Share of price categories.**  
5. **Price statistics.**  
6. **Dependency between price and rating.**  
7. **Distribution of product ratings.**  
8. **Share of products with and without ratings.**  
9. **Count of types, categories, and brands with ratings.**  
10. **Product type: number of products, average rating, average price.**  
11. **Category: number of products, average rating, average price.**  
12. **Relationships between product types and their categories.**  
13. **Brands by categories and product types with ratings.**  
14. **All brands: number of products, average rating, average price.**  
15. **Coverage of the top 20 brands in product distribution.**  
16. **Visualization of an excluded product.**  
17. **Top 20 brands offering the most products.**  
18. **Price distribution for the top 20 leading brands.**  
19. **Product distribution across price categories among top 20 brands.**  
20. **Product distribution across category-product types among top 20 brands.**

---

### **6. makeup_project_visualization_unloading_png.ipynb**
- A folder `makeup_visualizations_png` was created.
- Charts were exported as `.png` files for convenient review and demonstration.

---

### **7. makeup_presentation_pdf.ipynb**
- Creating the presentation `Makeup_analysis_presentation.pdf`.

---

### **8. makeup_README_Pipeline.ipynb**
- Creating and refining README.md and Pipeline.md.
