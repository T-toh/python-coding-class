```python
student_score=[60,60,50,70,95]
print(student_score)
```

    [60, 60, 50, 70, 95]
    


```python
student_score.count(60)
```




    2




```python
student_score.index(95)
```




    4




```python
#dictionary
student={"name": "titus", "age": 23,}
print(student["name"])
```

    titus
    


```python
print(student["age"])
```

    23
    


```python
student["height"]= 170.5
print(student)
```

    {'name': 'titus', 'age': 23, 'height': 170.5}
    


```python
movie={"title": "anaconda","type":"thriller","year":2004}
print(movie)
```

    {'title': 'anaconda', 'type': 'thriller', 'year': 2004}
    


```python
print(movie["title"])
```

    anaconda
    


```python
print(movie["type"])
```

    thriller
    


```python
my_bio = {"name":"Titus",
          "age": 25,
          "sex": "male",
          "skills":["bscn","data science", 'AI'],
          "Hobbies":('football','swimming','travelling'),
          'contacts':{"email":"waboit1@gmail.com", 'mobile':25470676666}
         }
print(my_bio)
```

    {'name': 'Titus', 'age': 25, 'sex': 'male', 'skills': ['bscn', 'data science', 'AI'], 'Hobbies': ('football', 'swimming', 'travelling'), 'contacts': {'email': 'waboit1@gmail.com', 'mobile': 25470676666}}
    


```python
print(my_bio["sex"])
```

    male
    


```python
my_bio["age"]=30
print(my_bio)
```

    {'name': 'Titus', 'age': 30, 'sex': 'male', 'skills': ['bscn', 'data science', 'AI'], 'Hobbies': ('football', 'swimming', 'travelling'), 'contacts': {'email': 'waboit1@gmail.com', 'mobile': 25470676666}}
    


```python
 my_bio["Hobbies"][1]
```




    'swimming'




```python
squares = {1:1, 2:4, 3:9, 4:16, 5:25}
print(squares)
```

    {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
    


```python
squares.popitem()
print(squares)
```

    {1: 1, 2: 4, 3: 9, 4: 16}
    


```python
print(squares.keys())
```

    dict_keys([1, 2, 3, 4])
    


```python
print(squares.values())
```

    dict_values([1, 4, 9, 16])
    


```python
squares.clear()
print(squares)
```

    {}
    


```python

```


```python

```
