
# Point system assignment

# Getting Started

To run this code you'll need to have a database , PHP dependencies

## Quick start

To quickly begin local development, follow these steps.

1. Clone the repository
```
git clone https://github.com/mishakansal/pointmanagement.git

or you can directly download it
```

2. make database connection by changing your database setting in application/config/database.php

````

default database name used: demo

```

3. Development site  to test on front end at http://localhost/canadadrive/test_api


## List of api's
1. To fetch list of user with their point according to point in decreasing order
```
http://localhost/canadadrive/api

```
2. To delete a user
```
http://localhost/canadadrive/api/delete

```
3. To view/edit user details
```
http://localhost/canadadrive/api/update

```
4. To add a new user
```
http://localhost/canadadrive/api/insert

```

5. To increase/decrease points on clicking +/- sign

```
http://localhost/canadadrive/api/updatepoints

parameter:
user-id,
point

```
