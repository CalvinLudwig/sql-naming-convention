# SQL Naming Convention
#### In a nutshell, all in snake_case and lowercase, table name in plural, column name in singular.
### Table name

- lowercase
- snake_case
- plural
###### Good
`'users', 'user_addresses'`
###### Bad
`'USERS', 'user', 'UserAddress'`

### Primary key auto increment
 - id always
 - lowercase
###### Good
`'id'`
###### Bad
`'idUser', 'user_id'`

### Column name
 - lowercase
 - snake_case
 - singular
 
###### Good
`'age', 'full_name'`
###### Bad
`'AGE', 'fullName', 'FULL_NAME', 'user_full_name'`

### Foreign key
 - name of the foreign table + id
 - snake_case
 - lowercase
 - singular
###### Good
`'user_id', 'user_address_id'`
###### Bad
`'idUser', 'idUserAddress', 'users_id', 'userId'`
