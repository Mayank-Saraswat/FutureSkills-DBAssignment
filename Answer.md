1. 'Product' and 'Product_Category' tables are related to each other based on id of product's category. A product belongs to which category can be find out using category id of 'Product' table, which is id for 'Product_Category' table. Using that id, product category name can be fetched.

2. To ensure that each product in the 'Product' table has a valid category assigned to it, NOT NULL property will be assgined to category_id column of 'Product' table during creation of schema.
