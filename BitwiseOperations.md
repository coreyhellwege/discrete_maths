# Bitwise Operations

Bitwise Operators allow you to manipulate data at it's most basic binary level. 

<hr>

![Bitwise Chart](/BitwiseChart.png)

<hr>

**AND**

- Returns 1 if each bit is 1, otherwise returns 0

```
1 1 0 0
1 0 1 0
-------
1 0 0 0 
```
<hr>

**OR**

- returns 1 if either or both bits are 1. Only returns 0 if both bits are 0

```
1 1 0 0
1 0 1 0
-------
1 1 1 0
```

<hr>

**XOR (EXCLUSIVE OR)**

- returns 1 only if both bits are different to eachother

```
1 1 0 0
1 0 1 0
-------
0 1 1 0
```

<hr>

**NOT**

- reverses the bit type. 1 will return 0 and 0 will return 1

```
1 0 1 0
-------
0 1 0 1
```