# Jasmin Suggestions

This is a list of suggestions of new features for Jasmin or updates/fixes that the Jasmin team might consider to deploy in the programming language

1) Being able to initialize array in a single instruction:

    e.g. Instead of using
    ```
    a[0] = 1;
    a[1] = 5;
    a[2] = 3;
    ```
    one could use
    ```
    a = [1,5,2];
    ```
2) The following error message should be more explicit regarding the variable name: *"Register allocation at line line 7: variable  _14.180 must be allocated to conflicting register RAX.61"*

3) Error messages typically say something like *"Error at line x (y-z)"* where *x* is the line and *y-z* are the offset inside that line where the error appears. Maybe instead of just having the offset, the error should show instead what is written in the code, so it is easier and faster to find the error

4) Implement *else if* or *elif*.
