# DSA_AMAZON_CASESTUDY

### This Casestudy is about data analysis of product and customer data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

#### Project Overview (DATASET DESCRIPTION)

The dataset contains information scraped from Amazon product pages, including:

• Product details: name, category, price, discount, and ratings

• Customer engagement: user reviews, titles, and content

• Each row represents a unique product, with aggregated reviewer data stored as comma-separated values

Total Records: 1,465 rows and TotalFields: 16 columns


- [Project Overiew](#project-overview)

- [Analysis Tools](#analysis-tools)

- [OUTCOME OF Order Data USING MICROSOFT EXCEL](#outcome-of-order-data-using-microsoft-excel)

- [OUTCOME OF ORDER_DATA USING Structured Query Language (SQL)](#outcome-of-order-data-using-structured-query-language-sql)

- [FINDINGS AND RECOMMENDATIONS](#findings-and-recommendations)


### Analysis Tool

- The main analysis tool for cleaning and analzing this dataset is Microsoft Excel [Download Here](https://www.microsoft.com)

This dataset is so dirty that i had to do so much cleaing processes such as:

- Deleted all unnecessary columns such as

About Product, User ID, User Name, Review Title, Review Content, Img Link and Product Link.
I thereafter proceeded to writing the Headings/Titles of each columns properly as some were in lower cases and there was an underscore symbol inserted too.
I proceeded to create new columns in order to clean the Category column as the names in it were too long. I did this by using the Text to Column tab, i therefore break the names into columns using delimiter. From this step I got the Product Column which consisted of the names of product that were embedded in the category column.

I also created new columns such as Price Bucket , Potential Revenue, Group Discount and Rating Score
#### Analysis Tasks

- Use pivot tables and calculated columns where necessary to answer the following:
  
        1. What is the average discount percentage by product category?

![image](https://github.com/user-attachments/assets/05db4300-bf37-4d8c-9886-2726419685ad)

 

        2. How many products are listed under each category?


![image](https://github.com/user-attachments/assets/eb64badd-d29b-48cd-97df-4420c26c5ff5)


        
        3. What is the total number of reviews per category?

![image](https://github.com/user-attachments/assets/7c79bd81-1ce8-4b38-a7ff-1f2d125eb621)
 

       4. Which products have the highest average ratings?

![image](https://github.com/user-attachments/assets/b990ef63-df19-47ac-89d8-638451c3fa96)



         5. What is the average actual price vs the discounted price by category?

![image](https://github.com/user-attachments/assets/63c8ffff-cf4f-4250-9c72-7763d25138c0)


         
          6. Which products have the highest number of reviews?


![image](https://github.com/user-attachments/assets/0dd68266-fb90-4a60-a8f0-91e2808e8d97)


           7. How many products have a discount of 50% or more?

	
![image](https://github.com/user-attachments/assets/b5f7f34f-7243-445d-837e-03a3977fe08f)



          8. What is the distribution of product ratings (e.g., how many products are rated 3.0,4.0, etc.)?


![image](https://github.com/user-attachments/assets/ad12fe32-8042-4fc7-b79a-2b00e9ebf5db)



          9. What is the total potential revenue (actual_price × rating_count) by category?

- For this question, I created a column on the Excel table called Potential Revenue

![Screenshot (32)](https://github.com/user-attachments/assets/0299d1da-da30-4b97-9576-606a76904a27)



        10. What is the number of unique products per price range bucket (e.g., <₹200,₹200–₹500, >₹500)?

![image](https://github.com/user-attachments/assets/daca1935-5722-4323-8334-eb309ad2bb21)


        11. How does the rating relate to the level of discount?

        
        12. How many products have fewer than 1,000 reviews?


        13. Which categories have products with the highest discounts?


  


13. Identify the top 5 products in terms of rating and number of reviews combined.


- [Project Overiew](#project-overview)



- [Analysis Tools](#analysis-tools)

- [OUTCOME OF Order Data USING MICROSOFT EXCEL](#outcome-of-order-data-using-microsoft-excel)

- [OUTCOME OF ORDER_DATA USING Structured Query Language (SQL)](#outcome-of-order-data-using-structured-query-language-sql)

- [FINDINGS AND RECOMMENDATIONS](#findings-and-recommendations)













e-commerce analytics solutions to sellers on platforms like Amazon. Your team has been
tasked with analysing product and customer review data to generate insights that can
guide product improvement, marketing strategies, and customer engagement.
2. Dataset Description
The dataset contains information scraped from Amazon product pages, including:
• Product details: name, category, price, discount, and ratings
• Customer engagement: user reviews, titles, and content
• Each row represents a unique product, with aggregated reviewer data
stored as comma-separated values
Total Records: 1,465 rows
TotalFields: 16 columns
3. Analysis Tasks
Use pivot tables and calculated columns where necessary to answer the following:
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <₹200,
