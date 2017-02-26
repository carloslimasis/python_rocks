## Concepts

### Declaring variables

In Python is very simple to declare a variable.
We can to declare variables this way:

```python
x = 20
```

Besides that, we can to declare more than one variable at the same time.

```python
x , y = 'value1', 1234
```

### Explicit declaration of variables

In Python doesn't not exists explicit declaration of variables. 
A variable only exists when we attribute a value to it.

### Snake_Case Pattern

The Python uses the Snake_Case pattern for variable names and/or identifiers.
See below some examples of Snake_Case variables:


```python
car_speed = 20
bicycle_speed = 10
```

### Numeric types

In Python we have 4 diferent numeric types:

- Integer

```python
number_backpacks = 10
```
- Long

```python
number_population = 10000L
```

- Float

```python
salary = 1000.00
```

- Complex

```python
coefficient = 123.12
```

### Strings

In Python we can to declare strings two ways:

- With single quotes

```python
name = 'Jonh'
```

- With double quotes

```python
name = "Maria"
```

### String Slice

The slice command is used for to slice any string:

```python
any_expression = 'a e i z u'
slice_expression = any_expression[4:5]
slice_expression
i
slice_expression = any_expression[6:9]
slice_expression
z u
```

### Print

We use the instruction ****print**** to print texts with the help of
wildcards.

```python
name = 'Carlos'
age = 25
print 'The %s age is %s' % (name, age)
```

When we try to concatenate a variable that dont be of String type and we use the command print, will occur a error because of the age variable type. Thus, is necessary use the wildcards.