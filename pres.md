# 1986

---

![inline](halley.jpg)

---

![inline](mir.jpg)

---

![inline](top-gun.jpg)

---

![inline](tiobe.png)

---

# David Hilbert
![inline](hilbert.jpg)

---

# David Hilbert
![inline](hilbert-paper.jpg)

---

# David Hilbert
![inline](hilbert-tomb.jpg)

---

# Kurt Gödel
![inline](godel.jpg)

---

# Kurt Gödel
![inline](godel-paper.jpg)

---

#[fit] "This statement is not provable"

---

##[fit] Is the Entscheidungsproblem decidable?
##[fit] What is decidable?

---

# Alonzo Church
![inline](alonzo-church.jpg)

---

# Alonzo Church
![inline](church-paper.png)

---

# Kurt Gödel
![inline](godel.jpg)

---

# Kurt Gödel
![inline](godel-kleene-tesis.png)

---

# Alan Turing
![inline](turing.jpg)

---

# Alan Turing
![inline](turing-paper.png)

---

#[fit] Church-Turing equivalence

---

# One problem, three equivalent solutions

## Lambda Calculus

---

<br>
<br>

```
L, M, N :=   x
        |    (lambda x. N)
        |    (L M)

```
---

# Booleans? If? Else? NUMBERS??

![inline](yo-dog.jpg)

---

# Booleans

```
true x y =
     x

false x y =
     y
```

---

# If then else

```
ifte bool t e =
     bool t e

```

---

# And

```
and p q =
    p q p

and true false =
    true false true
    
and false true =
    false true false

```
...

---

# Or

```
or p q =
   p p q

or true false =
   true true false
   
or false false =
   false false false

```

---

# We can build any construct with lambda calculus

## But how do we encode numbers?

---

```

zero f x = x
one  f x = f x
two  f x = f ( f x )
...
```

<br>

```
> two (+1) 0
2
```

---

# Addition

```

add m n f x = m f (n f x)

```
---

# Multiplication

```

mul m n f x = m (n f) x

```

---

# Remember, this is the 1940's
* Computers were actual people
* No compilers
* No programming language

---

# John McCarthy (1960's)

![inline](john-mccarthy.png)

---

# LISP

```
(LABEL FACT (LAMBDA (N)
    (COND ((ZEROP N) 1)
        (T (TIMES N (FACT SUB1 N))))))
```

---

# 1960s - 1990s

* Lots of programming languages
* Many them were functional
* Little collaboration

---

# 1990s - Paul Hudak

![inline](paul-hudak.jpg)

---

# Haskell Curry

![inline](haskell-curry.jpg)

---

# Haskell (1990)

![inline](haskell.png)

---

# 

---
