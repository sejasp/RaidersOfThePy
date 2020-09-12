# Major file types

## JSON

### Map (a.k.a. Dictionary object in Python)
```
{
    "name": "Captain Underpants",
    "f_name": "Captain",
    "l_name": "Underpants",
    "age": 10,
    "occupation": "World Domination"
}
```

### Lists

#### Integer List
```
[1, 2, 3, 4, 5, 6]
```

#### String list
```
['a', 'b', 'c', 'd']
```

#### List of Maps (Pretty)
```
[ 
    {
        "name": "Captain Underpants",
        "age": 10,
        "hometown": "America"
    },
    {
        "name": "Kal-El",
        "age": 30,
        "hometown": "Krypton"
    }
]
```

#### List of Maps (Condensed)
```
[
    {"name": "Captain Underpants", "age": 10, "hometown":"America"},
    {"name": "Kal-El", "age": 30, "hometown": "Krypton"}
]
```


## CSV

### Enclosed with double quotes, Delimited by comma
```
"name", "hometown", "age"
"Kal-El", "Krypton", 30
"Captain Underpants", "America", 10
```

### Only Delimited by comma, not enclosed
```
name, hometown, age
Kal-El, Krypton, 30
Captain Underpants, America, 10
