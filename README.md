# Machine-learning-datasets
 
 ## Import with Pandas 
  * Browse to the file in this repository
  * In the right corner, press 'Raw'
  * Copy URL, a valid `.csv` file path should start with `https://raw.githubusercontent.com/` and end with `.csv`
   ```python
   import pandas as pd
   data = pd.read_csv('https://raw.githubusercontent.com/katyperrycbt/Machine-learning-datasets/main/real_estate_data.csv')
   ```
 ## Sample (real_estate_data.csv)
   ```python
   data.head()
   ```
   
| tx_price | beds | baths | sqft | year_built | lot_size | property_type                 | exterior_walls      | roof                    | basement | restaurants | groceries | nightlife | cafes | shopping | arts_entertainment | beauty_spas | active_life | median_age | married | college_grad | property_tax | insurance | median_school | num_schools | tx_year |
|----------|------|-------|------|------------|----------|-------------------------------|---------------------|-------------------------|----------|-------------|-----------|-----------|-------|----------|--------------------|-------------|-------------|------------|---------|--------------|--------------|-----------|---------------|-------------|---------|
| 295850   | 1    | 1     | 584  | 2013       | 0        | Apartment / Condo / Townhouse | Wood Siding         |                         |          | 107         | 9         | 30        | 19    | 89       | 6                  | 47          | 58          | 33.0       | 65.0    | 84.0         | 234.0        | 81.0      | 9.0           | 3.0         | 2013    |
| 216500   | 1    | 1     | 612  | 1965       | 0        | Apartment / Condo / Townhouse | Brick               | Composition Shingle     | 1.0      | 105         | 15        | 6         | 13    | 87       | 2                  | 26          | 14          | 39.0       | 73.0    | 69.0         | 169.0        | 51.0      | 3.0           | 3.0         | 2006    |
| 279900   | 1    | 1     | 615  | 1963       | 0        | Apartment / Condo / Townhouse | Wood Siding         |                         |          | 183         | 13        | 31        | 30    | 101      | 10                 | 74          | 62          | 28.0       | 15.0    | 86.0         | 216.0        | 74.0      | 8.0           | 3.0         | 2012    |
| 379900   | 1    | 1     | 618  | 2000       | 33541    | Apartment / Condo / Townhouse | Wood Siding         |                         |          | 198         | 9         | 38        | 25    | 127      | 11                 | 72          | 83          | 36.0       | 25.0    | 91.0         | 265.0        | 92.0      | 9.0           | 3.0         | 2005    |
| 340000   | 1    | 1     | 634  | 1992       | 0        | Apartment / Condo / Townhouse | Brick               |                         |          | 149         | 7         | 22        | 20    | 83       | 10                 | 50          | 73          | 37.0       | 20.0    | 75.0         | 88.0         | 30.0      | 9.0           | 3.0         | 2002    |
