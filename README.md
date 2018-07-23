
# Combinations lab

## Introduction

Now, let's dive into combinations. In the previous section, we saw how the order was important. Cracking a code is one example, but what if the order doesn't matter, for example, when an engaged couple want to pick 3 wedding cakes from a list of 15? You'll need to use another technique here, and this is where combinations come in handy!



## Learning objectives

In this lab

- you'll learn about different situations where combinations can be used
- you'll create (easy) functions for combinations and permutations

## Let's get started

From the previous lab, you remember that we created a factorial function like this.

Now, let's use this factorial function to create a function `combination` as well as `permutation`, both holding 2 arguments n and k.


```python
def factorial(n):
    prod = 1
    while n >= 1:
        prod = prod * n
        n = n - 1
    return prod
```


```python
def permutation():
    None
```


```python
def combination():
    None
```

Great! We can use these functions in the following exercises.

## Exercise 1

Flatiron School is holding a mini mathematics contest, and there are 9 people in the last round. 

#### a. Imagine flatiron school is giving out bronze, silver and gold medal respectively. How many possible ways are there to create this top three?


```python
medal_top_3 = None
medal_top_3
```

#### b. Imagine Flatiron school granting the first three contestants a massive fruit basket. How many ways of selecting three people are there in this case?


```python
scholarship_top_3 = None
scholarship_top_3
```

## Exercise 2

Imagine you have 6 consonants and 4 vowels witten on a pieces of paper in a bag. You'll draw 5 letters out of the bag. 

#### a. What is the probability that you draw exactly 2 consonants and 3 vowels when drawing 5 letters?

Write the code for getting total number of ways of drawing 2 out of 6 and 3 out of 4 below


```python
draw_cons = None
draw_vow = None
```

The total number of ways to draw 5 letters out of 10 letters.


```python
sample = None
```

The probability of drawing 2 consonants and 3 vowels when drawing 5 letters:


```python
None
```

#### b. Out of 6 consonants and 4 vowels, how many words with 2 consonants and 3 vowels can be formed?

You can reuse a part of the previous exercise. Which part? print the result below.


```python
draw_cons = None
draw_vow = None
```

Now we need to take into account that order is important.


```python
order_5_letters = None
```

The total number of words with 2 consonants and 3 vowels then equals:


```python
total_words = None
print("In total,",  total_words, "words with 2 consonants and 3 vowels can be formed from our existing letter pool.")
```

## Exercise 3

We're holding a mini soccer tournament and 16 people are participating. We'd like to form 4 teams of 4. How many ways are there to do this?


```python
None
```


```python
None  # the answer is 2627625.0
```

# Sources 

https://brilliant.org/wiki/combinations/

https://www.geeksforgeeks.org/permutation-and-combination-in-python/
