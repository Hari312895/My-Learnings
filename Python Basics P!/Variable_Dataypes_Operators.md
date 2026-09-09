# Variable


### A variable is a container that stores a value, which can be changed during the execution of a program.


### Rules
#### >It can contain letters, numbers, and underscores.
#### >Spaces are not allowed.
#### >Variable names are case-sensitive (age and Age are different).
#### >Keywords cannot be used as variable names, such as if, for, while, class, etc


```python
name = "Hari" # str
age = 20 # int
height = 5.8 # float
is_student = True # boolean
print(name,age,height,is_student)
```

    Hari 20 5.8 True
    

# Datatype

### A dataype defines what type of value must be stored in an variable

#### Python has several built-in data types. The most commonly used basic data types are:

### 1. int (Integer)


```python
age = 20
age

```




    20



#### 2.str (String)
#### Used to store text or a sequence of characters.


```python
name = "Hari"
name
```




    'Hari'



#### 3. float (Floating Point)
#### Used to store decimal numbers.


```python
height = 5.8
height
```




    5.8



#### 4. bool (Boolean)
####          Used to store either True or false



```python
is_student = False
is_student
```




    False



## Checking Data Type
#### Python uses the type() function to check the type


```python
age = 20
(type(age))

```




    int



# Operators

## An operator is a symbol or keyword used to perform a specific operation on values or variables.

### 1.Arthimetic operator
### +, -, /, //(Floor division),%(mod),


```python
# mod
x=2
y=4
x%y
```




    2




```python
#floordivison
x=2
y=4
x//y
```




    0




```python
#division
x=2
y=4
x/y
```




    0.5




```python
x=2
y=4
x**y
```




    16



## 2.Comparison operator
### ==,!=,<,>,<=,


```python
x = 4
y = 6
print(x==y)
print(x!=y)
print(x<y)
print(x>y)
print(x<=y)
print(x>=y)
```

    False
    True
    True
    False
    True
    False
    

## 3.Logical operators
### and,or,not


```python
#and
x = True
y = False
x and y
```




    False




```python
#or
x = True
y = False
z = False
x or y or z
```




    True




```python
#not
x = True
not x
```




    False



## 4.Assissgnment Operator
### Assigning




```python
b = 40
b -= 5
b

```




    35




```python
a = 30 #Assiging the variable a value of 30
a += 20 # a = a(previous value of a)+20
a
```




    50




```python
c = 3
c *=3
c


```




    9




```python
d = 4
d //= 2
d
```




    2




```python

```
