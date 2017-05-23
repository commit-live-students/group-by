![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# Group By

The SQL GROUP BY clause is used in collaboration with the SELECT statement to arrange identical data into groups. This GROUP BY clause follows the WHERE clause in a SELECT statement and precedes the ORDER BY clause.

### Syntax

The basic syntax of a GROUP BY clause is shown in the following code block. The GROUP BY clause must follow the conditions in the WHERE clause and must precede the ORDER BY clause if one is used.

        SELECT column1, column2
        FROM table_name
        WHERE [ conditions ]
        GROUP BY column1, column2
        ORDER BY column1, column2

### Example

If you want to know name of all Customers group by City.

        SELECT CustomerName, City FROM Customers GROUP BY City;

