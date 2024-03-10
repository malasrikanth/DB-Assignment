### Read the diagram carefully and answer the below questions. ###

![ecommerce table](https://raw.githubusercontent.com/iAmritMalviya/DB-Assignment/main/product-management-ecommerce-table-.webp)

**Questions**

### 1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram. ###
A product category is a way for businesses to group and organise products or services they sell.when products are categorized,it is easier for customers to find what they are looking for on a website and employees to quickly refer to and find a product.

### 2. How could you ensure that each product in the "Product" table has a valid category assigned to it? ###
This will ensure that the value of the category_id column in the product table must be exit in the category table.This can be done by creating a foreign_key constraint on the category_id column in the product table that references the id colummn in the category table.

### 3. Create schema in any Database script or any ORM (Object Relational Mapping). ###
-Click File > Create Schema
-Enter a name for the schema
-Click Apply
-In the Apply SQL Script to Database window, click Apply to run the SQL command that creates the schema
Click Finish.



Steps: 
1. create the new public repository called DB-Assignment and make a file called Answers.md
   <br> for help: [How to create the repository in gitgub](https://www.geeksforgeeks.org/creating-repository-in-github/)
2. Answers to the 1st and 2nd questions will go to the Answer.md
3. The answer to the 3rd question will go to the schema.<language_extenstion> eg(schema.js, schema.java, schema.py, schema.sql etc)
4. upload it to the GitHub.
5. insert the link in the form.

