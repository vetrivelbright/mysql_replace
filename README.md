# mysql_replace

UPDATE comments SET comment = REPLACE(comment,"’","'")

Note: Where comments is a table name
comment - column name
comment - in this column find ’ or @ or # or any symbol and replace with text or alternative symbol


UPDATE products SET productDescription = REPLACE(productDescription,'abuot','about');

Note: Where products is a table name
productDescription - column name
productDescription - in this column find "abuot" word and replace with "about"
