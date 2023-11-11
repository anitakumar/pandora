# 
## Code to  create synthetic data for customers buying pandora jewellery
Uses the python [Faker library](https://faker.readthedocs.io/en/master/) to generate the synthetic data
It generates columns based on the product_types
The columns are as follows 
|       Column_name       |
|:-----------------------:|
| Customer_id             |
| order_id                |
| prev_charms_count       |
| this_charm_count        |
| prev_bracelet_count     |
| this_bracelet_count     |
| prev_rings_count        |
| this_rings_count        |

If you add more product_types you will see additional column.
The code should produce the same dataset each time the code is executed.

## Assumptions
1. Only date is used not datetime
2. No duplicate rows

### How to create synthetic data
1. Open a Jupyter notebook pandora_synthetic_data.ipynb
2. !pip install faker
3. In the main section you can customize the inputs as follows

#### Inputs parameters in the main section

|       Input      |            description            |
|:-----------------|:---------------------------------:|
| number_of_rows   | number of rows of data to generate|
| product_types    | products types example rings      |
| customer_data    | data frame with customer_id column|

#### Outputs

The ouputs will be in outputs/out.csv folder

