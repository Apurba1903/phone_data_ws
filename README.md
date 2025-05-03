# Smartprix Dataset Documentation  

## 📌 About Smartprix  
[Smartprix](https://www.smartprix.com/) is a leading Indian price comparison website that tracks products across e-commerce platforms. It specializes in electronics like smartphones, laptops, and gadgets, providing:  
- **Real-time price tracking**  
- **Product specifications**  
- **User reviews and ratings**  
- **Deal alerts**  

This dataset contains smartphone specifications scraped from Smartprix, useful for price analysis, feature comparisons, and market research.  

---

## 📊 Column Descriptions  

| Column      | Description | Example Values |  
|-------------|------------|----------------|  
| **model**   | Smartphone model name | "iPhone 15", "Samsung Galaxy S23" |  
| **price**   | Current price in INR (₹) | 79999, 58990 |  
| **rating**  | Average user rating (out of 5/10) | 4.2, 3.8 |  
| **sim**     | SIM card type | "Dual Nano-SIM", "eSIM" |  
| **processor** | Chipset/CPU | "Snapdragon 8 Gen 2", "Apple A16 Bionic" |  
| **ram**     | RAM capacity in GB | 8, 12, 16 |  
| **battery** | Battery capacity (mAh) | 5000, 4500 |  
| **display** | Screen size & type | "6.7\" AMOLED", "6.1\" Super Retina XDR" |  
| **camera**  | Camera setup (MP) | "50MP + 12MP + 12MP", "48MP Triple Cam" |  
| **card**    | Expandable storage support | "microSD up to 1TB", "No" |  
| **os**      | Operating system | "Android 13", "iOS 17" |  

---

## 🛠️ Potential Use Cases  
1. **Price Trend Analysis**  
2. **Feature vs. Price Correlation**  
3. **Brand Comparison** (Apple vs. Samsung vs. OnePlus)  
4. **Recommender Systems**  

---

## ℹ️ Data Notes  
- **Source**: [Smartprix Mobile Section](https://www.smartprix.com/mobiles/) 

--- 

```python
# Sample code to load the dataset
import pandas as pd
df = pd.read_csv("smartprix_phones.csv")
print(df.head())
```  