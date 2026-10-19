# SQL CRUD

This directory contains SQL exercises focused on creating, querying, and manipulating data in a SQLite database.

## Topics

- Creating tables
- Inserting records
- Selecting data
- Selecting specific columns
- Filtering rows with `WHERE`
- Combining conditions with `AND` and `OR`
- Updating records
- Deleting records
- Sorting results with `ORDER BY`
- Limiting results with `LIMIT`
- Aggregate functions
- Grouping data with `GROUP BY`
- CRUD operations

## Files and Description

| **File** | **Description** |
| -------- | --------------- |
| `0-create_table.sql` | Creates the `books` table with the required columns and constraints. |
| `1-insert_data.sql` | Inserts the specified book records into the `books` table. |
| `2-select_all.sql` | Retrieves all columns and rows from the `books` table. |
| `3-select_columns.sql` | Retrieves the title and price of each book. |
| `4-filter_by_genre.sql` | Retrieves titles and authors of books in the Tech genre. |
| `4-filter_by_price.sql` | Retrieves titles and prices of books priced above 20. |
| `4-filter_with_and.sql` | Retrieves Tech books priced above 30. |
| `4-filter_with_or.sql` | Retrieves books in the Fantasy genre or priced below 10. |
| `5-update_by_id.sql` | Updates the price of the book with a specified ID. |
| `5-update_by_condition.sql` | Increases stock for books published before 2000. |
| `5-update_with_and.sql` | Reduces the price of qualifying Tech books by 10%. |
| `6-delete_by_id.sql` | Deletes the book with the specified ID. |
| `6-delete_by_condition.sql` | Deletes books with no stock available. |
| `6-delete_with_and.sql` | Deletes books published before 1950 and priced below 9. |
| `7-order_by_price_asc.sql` | Lists book titles and prices in ascending price order. |
| `7-order_by_year_desc.sql` | Lists book titles and publication years in descending year order. |
| `7-limit_results.sql` | Retrieves the three cheapest books. |
| `7-order_and_limit.sql` | Retrieves the five books with the highest stock. |
| `8-count_books.sql` | Counts the total number of books. |
| `8-average_price.sql` | Calculates the average book price. |
| `8-max_stock.sql` | Finds the highest stock value. |
| `8-total_stock.sql` | Calculates the total number of units in stock. |
| `8-min_price.sql` | Finds the lowest book price. |
| `9-count_by_genre.sql` | Counts books in each genre. |
| `9-average_price_by_genre.sql` | Calculates the average price for each genre. |
| `9-total_stock_by_genre.sql` | Calculates total stock for each genre. |
| `9-count_by_author.sql` | Counts books by each author. |
| `10-select_tech_books.sql` | Retrieves technical books published in or after 2000. |
| `10-increase_stock.sql` | Adds three units to books with fewer than five in stock. |
| `10-delete_zero_stock.sql` | Deletes books that have no stock available. |
| `10-cheapest_available.sql` | Retrieves the four cheapest books currently in stock. |
| `10-stock_by_genre.sql` | Calculates total stock for each genre. |
| `10-average_price_by_genre.sql` | Calculates the average price for each genre. |
