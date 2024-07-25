# Advance-PHP-Ajax-CRUD
PHP AJAX CRUD with Image Upload


### ****Creating the Database Table****

Create a table named *users* inside your MySQL database using the following code.

```sql
CREATE TABLE `addusers` (
  `id` int(255) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `image` varchar(255) NOT NULL,
  `country` varchar(255) NOT NULL,
  `gender` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
)
```
