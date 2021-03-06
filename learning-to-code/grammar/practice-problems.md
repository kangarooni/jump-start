# Practice problems
_JumpStart: Lesson 9_

## Overview
Complete each section by hand, then check your answers using `irb`

## Variables and assignment practice

```ruby
x = 5
# what value does x now hold?

##5

z = "Hello"
# what value does z now hold?

## z

a = 5
b = 3.2
c = a + b
# what values does c now hold?

## 8.2

var1 = "lawl"
var2 = "brb"
# what value does var2 now hold?

## brb 

e = 6 + 3
# what values does e now hold?

## 9

f = 3.5
f = f + 2
# what value does f now hold?

## 5.5

poodle = 4
pitbull = 3
# what value does boxer now hold?

h = 5
h = h + h
# what values does h now hold?

##10

j = 1
k = 2
m = 3
n = j + k + m
# what value does n now hold?

## 6

l = "moo"
q = "quack"
l  = q
# what value does l now hold?

## quak 

r = "moo"
s = "quack"
t = "woof"
r = t
# what value does r now hold?

## woof

u = 5
u = u * 2
## 10
u = u * 2
## 20
u = u * 2
# what value does u now hold?

## 40

v = "b"
z = "a"
# what value does v now hold?

## b

aa = 3234
bb = 2398
cc = 0
dd = (aa + bb) / cc
# what value does dd now hold?

## error

yy = 7
zz = yy % 2
# what value does zz now hold?

## 1

ee = 12
ff = ee % 4
# what value does ff now hold?

## 0 

zz = 17
hh = zz % 3
# what value does hh now hold?

## 2

```


## Operators practice
Consider the following variable assignments and then fill in the tables

```ruby
d = 10
e = 5.0
f = 2
g = 11.0
h = 3
i = 1.5
```

| Operation | Result | Data type of result |
| :---: | :---:| :---: |
| `d + e` |15.0|F|
| `f + h` |5|I|
| `g + h` |14.0|F|
| `d - f` |5.0|F|
| `g - e` |9.0|F|
| `(h + i) - f` |2.5|F|
| `(d - f) + e` |13.0|F|
| `d * f` |20|I| |
| `g * i` |16.5|F| |
| `f * g` |22.0|F| |
| `d / f` |5|I| |
| `d / e` |2.0|F| |
| `e / f` |2.5|F| |
| `(g * f) / f` |11.0|F| |
| `(d / f) * e` |25.0|F| |
| `21 / 5` |4.2|F| |
| 14 / 5 |2.8|F| |
| 10 % 3 |1|I| |
| 20 % 2 |0|I| |
| 4 % 5 |0|I| |
| 8 % 1 |0|I| |

## String practice
Determine the output for each of the following problems on your own and then check your answer using `irb`

```ruby
# problem 1
my_string = "I love Seattle"
my_string.slice(7)

## S

# problem 2
my_string = "I love Seattle"
my_string.slice(2, 4)

##love

# problem 3
my_string = "I love Seattle"
my_string.slice("Seattle")

##nil

# problem 4
my_string = "Ada"
my_string += " Lovelace"

## Ada Lovelace

# problem 5
my_string = "Ada"
my_string << " codes" << " it!"

## Ada codes it!

# problem 6
my_string = "Ada"
my_string.concat(" likes to code").slice(4...9)

## Ada likes to code
## likes

# problem 7
my_string = "Hello world"
"Goodbye " + my_string.slice(6, 5) << "!"

## Goodbye world

# problem 8
my_string = "Hello world!"
my_string.slice(0...5).concat(", goodbye!")

## Hello, goodbye!

# problem 9
my_string = "Hello world!"
my_string.slice(0) << "i" + "!"

## Hi!

# problem 10
my_string = "I love Ruby"
my_string.slice(7, 4).concat(my_string.slice(2..5)) + my_string.slice(0)

## Ruby love I

# problem 11
my_string = "I love Ruby"
my_string.slice(7, 4).concat(my_string.slice(2...6)) + my_string.slice(0)

## Ruby love I
### three dots is noninclusive of last

# problem 12
my_string = "I love Ruby"
"R".concat(my_string.slice(8, 3) + " rocks!")

## Ruby rocks!

# problem 13
my_string = "I love Ruby"
my_string.slice(2, 4) << my_string.slice(7...11).concat(my_string.slice(2...6))

## love Ruby love

```
