Problem Statement:
One of the largest retail chains in the world wants to use their vast data source to build an efficient forecasting model to predict the sales for each SKU in its portfolio at its 76 different stores using historical sales data for the past 3 years on a week-on-week basis. Sales and promotional information is also available for each week - product and store wise.


Data Variables Description:
record_ID: Unique ID for each week store sku combination
week: Starting Date of the week
store_id: Unique ID for each store (no numerical order to be assumed)
sku_id: Unique ID for each product (no numerical order to be assumed)
total_price: Sales Price of the product 
base_price: Base price of the product
is_featured_sku: Was part of the featured item of the week
is_display_sku: Product was on display at a prominent place at the store
units_sold(Target): Total Units sold for that week-store-sku combination
