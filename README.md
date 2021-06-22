# Live Coding 

## Core PHP Questions


### String Manipulation Part 1
Take the following string:
```
API_REFERENCE_CODE:6330d8f60f9b618e77801user=55555%3A507a7bb3578cea53068d7248ab787ef4Tracker-Key:93cbce10db1aa79e29b33aec476dd6baStrict-Transport-Security: max-age=63072000
```
Using PHP, extract and echo the following section:
```
user=55555%3A507a7bb3578cea53068d7248ab787ef4
```

Rules:
You must use core PHP functions.
If you know the PHP function you wish to use but do not remember the syntax, you are allowed to google that function. 

### String Manipulation Part 2
Using the string that you extracted above, write a function that will strip out all of the non-numeric characters and then echo out the resulting string.


### Database Question 
Please write a SQL query to find the second highest salary in the following table:
```
|-----------------------|
|     Employees         |
|-----------------------|
|  id                   |
|  name                 |
|  salary               |
|  date_hired           |
|-----------------------|
```
