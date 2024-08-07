```python
#string concatination
str1= "hello"
str2= "world"
result= str1+ " "+ str2
print(result)
```

    hello world
    


```python
#string multiplication
str1= "hello"
result= str1* 3
print(result)
```

    hellohellohello
    


```python
#string indexing
str1= "titus"
str1[0]
```




    't'




```python
city_names=["Nanyuki","Kisumu","Mombasa","nakuru","nyeri", "malindi"]
print(city_names)

```

    ['Nanyuki', 'Kisumu', 'Mombasa', 'nakuru', 'nyeri', 'malindi']
    


```python
city_area=[55000,12000,70000]
print(city_area)
```

    [55000, 12000, 70000]
    


```python
city_names[2:6]
```




    ['Mombasa', 'nakuru', 'nyeri', 'malindi']




```python
print(city_names[0])
```

    Nanyuki
    


```python
shopping=("banana","carrots","apple")
print(shopping.split(","))
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[41], line 2
          1 shopping=("banana","carrots","apple")
    ----> 2 print(shopping.split(","))
    

    AttributeError: 'tuple' object has no attribute 'split'



```python
city_names.append("Muranga")
print(city_names)
```

    ['Nanyuki', 'Kisumu', 'Mombasa', 'Muranga']
    


```python
student_age=[12,13,17,19,22,21]
print(student_age)
```

    [12, 13, 17, 19, 22, 21]
    


```python
student_age.remove(12)
print(student_age)

```

    [13, 17, 19, 22, 21]
    


```python
student_age.append(23)
print(student_age)


```

    [12, 13, 17, 19, 22, 21, 23]
    


```python
student_age.sort()
print(student_age)
```

    [12, 13, 17, 19, 21, 22, 23]
    


```python
student_age.sort(reverse=True)
student_age
```




    [23, 22, 21, 19, 17, 13, 12]




```python
print(student_age[:2])
```

    [23, 22]
    


```python
print(student_age[2:])
```

    [21, 19, 17, 13, 12]
    


```python
student_age[0]= 25
print(student_age)
```

    [25, 22, 21, 19, 17, 13, 12]
    


```python
str3="carrot,banana,tomato"
print(str3)
```

    carrot,banana,tomato
    


```python
grocery=str3.split(",")
print(grocery)
```

    ['carrot', 'banana', 'tomato']
    


```python
print(str3.upper())
```

    CARROT,BANANA,TOMATO
    


```python
print(str3[1])
```

    a
    


```python
print(str3.replace("banana","garlic"))
```

    carrot,garlic,tomato
    


```python
str4= "hello world"
str4
```




    'hello world'




```python
str4= "Hello\tWorld"
print(str4)
```

    Hello	World
    


```python
str4 = "Hello\nWorld"
print(str4)
```

    Hello
    World
    


```python

```
