<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# Project Summary

I've posted all my answers here in the details tag after each question.

## Table - person

### Instructions
1. Create a table called person that records a person's id, name, age, height ( in cm ), city, favorite_color. 
    * id should be an auto-incrementing id/primary key - Use type: SERIAL

<details>

    ```sql
    
    ```
</details>

2. Add 5 different people into the person database. 
    * Remember to not include the person_id because it should auto-increment.

<details>

    ```sql
    
    ```
</details>

3. List all the people in the person table by height from tallest to shortest.

<details>

    ```sql
    
    ```
</details>

4. List all the people in the person table by height from shortest to tallest.

<details>

    ```sql
    
    ```
</details>

5. List all the people in the person table by age from oldest to youngest.

<details>

    ```sql
    
    ```
</details>

6. List all the people in the person table older than age 20.

<details>

    ```sql
    
    ```
</details>

7. List all the people in the person table that are exactly 18.

<details>

    ```sql
    
    ```
</details>

8. List all the people in the person table that are less than 20 and older than 30.

<details>

    ```sql
    
    ```
</details>

9. List all the people in the person table that are not 27 (Use not equals).

<details>

    ```sql
    
    ```
</details>

10. List all the people in the person table where their favorite color is not red.

<details>

    ```sql
    
    ```
</details>

11. List all the people in the person table where their favorite color is not red and is not blue.

<details>

    ```sql
    
    ```
</details>

12. List all the people in the person table where their favorite color is orange or green.

<details>

    ```sql
    
    ```
</details>

13. List all the people in the person table where their favorite color is orange, green or blue (use IN).

<details>

    ```sql
    
    ```
</details>

14. List all the people in the person table where their favorite color is yellow or purple (use IN).

<details>

    ```sql
    
    ```
</details>


## Table - orders

### Instructions

1. Create a table called orders that records: order_id, person_id, product_name, product_price, quantity.

<details>

    ```sql
    
    ```
</details>

2. Add 5 orders to the orders table.
    * Make orders for at least two different people.
    * person_id should be different for different people.

<details>

    ```sql
    
    ```
</details>

3. Select all the records from the orders table.

<details>

    ```sql
    
    ```
</details>

4. Calculate the total number of products ordered.

<details>

    ```sql
    
    ```
</details>

5. Calculate the total order price.

<details>

    ```sql
    
    ```
</details>

6. Calculate the total order price by a single person_id.

<details>

    ```sql
    
    ```
</details>


## Table - artist

### Instructions

1. Add 3 new artists to the artist table. ( It's already created )

<details>

    ```sql
    
    ```
</details>

2. Select 10 artists in reverse alphabetical order.

<details>

    ```sql
    
    ```
</details>

3. Select 5 artists in alphabetical order.

<details>

    ```sql
    
    ```
</details>

4. Select all artists that start with the word 'Black'.

<details>

    ```sql
    
    ```
</details>

5. Select all artists that contain the word 'Black'.

<details>

    ```sql
    
    ```
</details>


## Table - employee

### Instructions

1. List all employee first and last names only that live in Calgary.

<details>

    ```sql
    
    ```
</details>

2. Find the birthdate for the youngest employee.

<details>

    ```sql
    
    ```
</details>

3. Find the birthdate for the oldest employee.

<details>

    ```sql
    
    ```
</details>

4. Find everyone that reports to Nancy Edwards (Use the ReportsTo column).
   * You will need to query the employee table to find the Id for Nancy Edwards

<details>

    ```sql
    
    ```
</details>

5. Count how many people live in Lethbridge.

<details>

    ```sql
    
    ```
</details>



## Table - invoice 

### Instructions

1. Count how many orders were made from the USA.

<details>

    ```sql
    
    ```
</details>

2. Find the largest order total amount.

<details>

    ```sql
    
    ```
</details>

3. Find the smallest order total amount.

<details>

    ```sql
    
    ```
</details>

4. Find all orders bigger than $5.

<details>

    ```sql
    
    ```
</details>

5. Count how many orders were smaller than $5.

<details>

    ```sql
    
    ```
</details>

6. Count how many orders were in CA, TX, or AZ (use IN).

<details>

    ```sql
    
    ```
</details>

7. Get the average total of the orders.

<details>

    ```sql
    
    ```
</details>

8. Get the total sum of the orders.

<details>

    ```sql
    
    ```
</details>
