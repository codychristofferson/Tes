# Live Coding 

## Core PHP Questions

The string used in this exercise is from the header of an actual cUrl request we make several times a day to retrieve a user token that is used for interacting with a third party API. In this exercise, we will see how you would extract the user key. One thing to note: The number after max-age= is dynamic, so using str_replace is not a valid option for solving this question.


### String Manipulation Part 1
Take the following string:
```
SetCookie:user=55555%3A507a7bb3578cea53068d7248ab787ef4%3A%3A00000000-0000-0000-0000-000000000000%3A00000000-0000-0000-0000-000000000000%3AStrict-Transport-Security: max-age=63072000
```
Using PHP, extract and echo the following section:
```
user=55555%3A507a7bb3578cea53068d7248ab787ef4%3A%3A00000000-0000-0000-0000-000000000000%3A00000000-0000-0000-0000-000000000000%3A
```


### String Manipulation Part 2
Using the string that you extracted above, write a function that will strip out all of the non-numeric characters and then echo out the resulting string.

