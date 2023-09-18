# Introduce my Github repository
```
  https://github.com/MaximeLionel/PythonCourse
```
![](\_res/2023-09-13-12-45-00.png)


# Interpret HelloWorld.py
```
  print ('Hello World! Greetings from Yahha')
```
1. the ending .py indicates that the file is a Python program.
2. IDE choose the correct interpretor.
3. Interpret parse each word in the file.
4. Interpret execute as parsing result.

# Variables - 变量
* You’ll also learn how to store your data in variables and how to use those variables in your programs.
* Python variables do not need explicit declaration to reserve memory space or you can say to create a variable. A Python variable is created automatically when you assign a value to it. The equal sign (=) is used to assign values to variables.
* The operand to the left of the = operator is the name of the variable and the operand to the right of the = operator is the value stored in the variable.
* Example:
```
    a = "Yahaha is fat and need to lose weight!"
    print(a)
```
  1. On 1st line, Python interpretor associates the text “Hello Python world!” with the variable message.
  2. On 2nd line, it prints the value associated with message to the screen.
* The variable value can be changed:
  ```
    a = "Yahaha is fat and need to lose weight!"
    print(a)

    a = "Definitely!!!"
    print(a)
  ```

# Naming Rules
* Variable name contains only letters, numbers, and underscores.
* Variable name can only start with letters or underscores.
* Spaces are not allowed.
* Python keywords and function names are not allowed.
* Be short and descriptive.
* invalid
  ```
    1yahaha = 100
    $yahaha  = 100
    yahaha-coder = "brilliant"
  ```
* valid
  ```
    yahaha = 888
    _yahaha  = 6666
    yahaha1 = "coder"
    YahahaAge  = 40
    yahaha_monthlysalary = 1000000
  ```

# Common mistakes
* letter mistake:
  ```
    anouncement = "Yahaha is fat and need to lose weight!"
    print(anouncment) # wrong spell
  ```

# Homework
Store a message in a variable, and print that message . Then change the value of your variable to a new message, and print the new message .



# Delete Variables
* Use 'del' to delete variable.
```
    del var
    del var_a, var_b
```
```
    counter = 100
    print (counter)

    del counter
    print (counter)
```

# Python Reserved/Key Words
![](\_res/2023-09-12-23-05-28.png)

* The following list shows the Python keywords. These are reserved words and you cannot use them as constant or variable or any other identifier names. 
* All the Python keywords contain lowercase letters only.


# Tips
## Spacing / additional line
```
    a = 2 + 2

    or 

    a = 2
    + 2

    a = 2 \
    +2
```
* a line of code must be in the same line.
* You may choose to use continuation character (\\) to continue the line.

## Indentation sensitive
```
    if True:
        print ("True")
    else:
        print ("False")

    or 

    if True:
    print ("Answer")
    print ("True")
    else:
    print ("Answer")
    print ("False")
```

# Comment - 注释
* use '#'
* good habit of commenting

# Python Local Variable
* Python Local Variables are defined inside a function. We can not access variable outside the function.
```
    def sum(x,y):
        total = x + y
        return sum
    print(sum(5, 10))
```

# Python Global Variable
* Any variable created outside a function can be accessed within any function and so they have global scope.
```
    x = 5
    y = 10
    def sum():
        sum = x + y
        return sum
    print(sum())
```

# Control

| Operator      | Meaning | Example     |
| :---        |    :----:   |          ---: |
| ==      | Equals       |  x == y  |
| !=   | Not Equal        | x != y  |
| <   | Less Than        | x < y  |
| >   | Greater Than        | x > y  |
| <=   | Less Than or Equal to   | x <= y  |
| >=   | Greater Than or Equal to   | x >= y |
