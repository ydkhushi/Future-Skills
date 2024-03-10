Questions

Q1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans.
1. The relationship between "Product" and "Product_Category" entities is a "many-to-one" relationship.
2. This implies that many products can belong to one category.
3. It facilitates efficient organization and classification of products.
4. Changes made to category details reflect consistently across all associated products.
5. Ensures data integrity and coherence within the database.

Q2. How could you ensure that each product in the "Product" table has a valid category assigned to it?
Ans.
To ensure each product in the "Product" table has a valid category. We will use concept of Referential Integrity for ensuring consistency 
and accuracy of data relationships between tables . It's enforced through various mechanisms, primarily foreign key constraints

1 .Implement a foreign key constraint between the "Product" and "Product_Category" tables or else we can implement similar thing using stored procedure.
ex ALTER TABLE Product
ADD CONSTRAINT FK_Product_Category
FOREIGN KEY (category_id)
REFERENCES Product_Category(category_id);

2. Any attempt to assign an invalid category will be rejected by the database system, maintaining data integrity.
3. Maintaining Data Consistency
In summary, by using referential integrity through foreign key constraints, the database ensures 
that each product in the "Product" table has a valid category assigned to it. This approach not only guarantees 
data consistency and accuracy but also simplifies data management
and maintenance in the long run.




