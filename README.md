# 📘 PA 3 – Programming Assignment  

👨‍💻 Author: Joshua de Guzman <br>  
📅 Date: September 12, 2024 <br>  
📚 Course: ECE2112 – Programming Assignment  

---

# 📌 Version History  

- **V1.0 (09-12-24)** – Initial Release and Submission of GitHub Link  
- **V1.1 (09-13-24)** – Added README Documentation for Problems  
- **V1.2 (09-14-24)** – Added Code Snippets and Outputs in README  

---

# 📌 Problem 1: Pandas DataFrame Loading  

This problem loads the **Cars dataset** into a Pandas DataFrame named `cars` and displays the first and last five rows.  

### Steps:  
1. Import `pandas` as `pd`.  
2. Load the dataset `Cars.csv` into a DataFrame named `cars`.  
3. Display the **first 5 rows** using `.head()`.  
4. Display the **last 5 rows** using `.tail()`.  

---

## ✅ Input:  
```python
# PA 3 – Problem 1: Load Cars Dataset

import pandas as pd

# Load dataset
cars = pd.read_csv("Cars.csv")

# Display the first 5 rows
print("First five rows of cars:")
print(cars.head())

# Display the last 5 rows
print("\nLast five rows of cars:")
print(cars.tail())
```

First five rows of cars:
        Model   mpg  cyl  disp   hp  drat     wt  qsec  vs  am  gear  carb
0   Mazda RX4  21.0    6   160  110  3.90  2.620  16.46   0   1     4     4
1   Mazda RX4 Wag  21.0  6  160  110  3.90  2.875  17.02   0   1  4  4
2   Datsun 710  22.8  4  108   93  3.85  2.320  18.61   1   1  4  1
3   Hornet 4 Drive  21.4  6  258  110  3.08  3.215  19.44   1   0  3  1
4   Hornet Sportabout  18.7  8  360  175  3.15  3.440  17.02   0   0  3  2

Last five rows of cars:
          Model   mpg  cyl  disp   hp  drat     wt  qsec  vs  am  gear  carb
27   Porsche 914-2  26.0  4  120.3  91  4.43  2.140  16.7   0  1  5  2
28  Lotus Europa  30.4  4  95.1  113  3.77  1.513  16.9   1  1  5  2
29  Ford Pantera L  15.8  8  351  264  4.22  3.170  14.5   0  1  5  4
30  Ferrari Dino  19.7  6  145  175  3.62  2.770  15.5   0  1  5  6
31  Maserati Bora  15.0  8  301  335  3.54  3.570  14.6   0  1  5  8
