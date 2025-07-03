# DSA_AMAZON_CASESTUDY

### This Casestudy is about data analysis of product and customer data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

- [Project Overiew](#project-overview)

- [Analysis Tools](#analysis-tools)

- [Exploratory Details](#eploratory-details)

- [Outcome of Amazon Product Data Using Microsoft Excel](#outcome-of-amazon-product-data-using-microsoft-excel)

- [DASHBOARD OVERVIEW](#dashboard-overview)


#### Project Overview

- (DATASET DESCRIPTION)

The dataset contains information scraped from Amazon product pages, including:

• Product details: name, category, price, discount, and ratings

• Customer engagement: user reviews, titles, and content

• Each row represents a unique product, with aggregated reviewer data stored as comma-separated values. Total Records: 1,465 rows and TotalFields: 16 columns



#### Analysis Tool

- The main analysis tool for cleaning and analzing this dataset is Microsoft Excel [Download Here](https://www.microsoft.com)


#### Exploratory Details

This dataset is so dirty that i had to do so much cleaing processes such as:

- Deleted all unnecessary columns such as: About Product, User ID, User Name, Review Title, Review Content, Img Link and Product Link.

- I thereafter proceeded to writing the Headings/Titles of each columns properly as some were in lower cases and there was an underscore symbol inserted too.

- I also created new columns in order to clean the Category column as the names in it were too long. I did this by using the Text to Column tab,
  i therefore break the names into columns using delimiter. From this step I got the Product Column which consisted of the names of product that were embedded in the category column.

- Finally, I  created new columns such as Price Bucket , Potential Revenue, Group Discount and Rating Score

#### Outcome of Amazon Product Data Using Microsoft Excel

- Analysis Tasks

       - Use pivot tables and calculated columns where necessary to answer the following:
  
        1. What is the average discount percentage by product category?

![image](https://github.com/user-attachments/assets/bf63b81d-057e-4311-9319-bab030dd25b2)

 
        2. How many products are listed under each category?

![image](https://github.com/user-attachments/assets/2056163b-5f72-4ba5-b900-884155b40d6c)


        
        3. What is the total number of reviews per category?

![image](https://github.com/user-attachments/assets/8a680f63-a26c-4408-8175-3c5fc5d3fbbb)

 

       4. Which products have the highest average ratings?

![image](https://github.com/user-attachments/assets/77d0f089-1447-4839-9913-732a2a77f1f2)


         5. What is the average actual price vs the discounted price by category?

![image](https://github.com/user-attachments/assets/845065a7-dc45-47a1-b2d9-94b893726aa9)


         
          6. Which products have the highest number of reviews?

![image](https://github.com/user-attachments/assets/1c79b1a1-3a29-4726-81fc-b863a2a747cc)

         
	   7. How many products have a discount of 50% or more?


![image](https://github.com/user-attachments/assets/44e14636-8231-4764-a1ce-d2e2e4af8cac)


          8. What is the distribution of product ratings (e.g., how many products are rated 3.0,4.0, etc.)?

![image](https://github.com/user-attachments/assets/2d3520ab-fd91-423b-a1e9-edef459d24fd)



          9. What is the total potential revenue (actual_price × rating_count) by category?

- For this question, I created a column on the Excel table called Potential Revenue

![Screenshot (32)](https://github.com/user-attachments/assets/0299d1da-da30-4b97-9576-606a76904a27)



        10. What is the number of unique products per price range bucket (e.g., <₹200,₹200–₹500, >₹500)?

![image](https://github.com/user-attachments/assets/daca1935-5722-4323-8334-eb309ad2bb21)


        11. How does the rating relate to the level of discount?

![image](https://github.com/user-attachments/assets/79f52cb1-5f46-46d1-ada1-97d19f924b93)

- The rating generally remains high across various levels of discount. This suggests that the rating does not consistently decrease or increase in a linear fashion with the level of discount, but rather 
 tends to stay within a relatively high range,
  
	
        12. How many products have fewer than 1,000 reviews?

- All the products have fewer than 1,000 reviews 
       
	
 
        13. Which categories have products with the highest discounts?

![image](https://github.com/user-attachments/assets/f3515b71-6a8a-4b32-8c94-37bde0a07929)


![image](https://github.com/user-attachments/assets/eb2c125b-6789-411a-a48b-8015e261d86a)
  


       14. Identify the top 5 products in terms of rating and number of reviews combined.

![image](https://github.com/user-attachments/assets/2c0fb1ce-e66b-41cf-b168-fd36de79296f)



#### DASHBOARD OVERVIEW

![Screenshot (34)](https://github.com/user-attachments/assets/ae8f7778-93b2-4a67-b7ac-1aecb158014c)


