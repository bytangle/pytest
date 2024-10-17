### Interview Questions:

**Instructions**

- Write your code on jupyter notebook online. 

- https://jupyter.org/try-jupyter/lab/

---

**Question 1:**

You are given an array of objects, where each object represents a month belonging to a particular year. Like this

```python
data = [
    {'year': 2019, 'month': 'January'},
    {'year': 2019, 'month': 'February'},
    {'year': 2019, 'month': 'March'},
    {'year': 2019, 'month': 'April'},
    {'year': 2020, 'month': 'January'},
    {'year': 2020, 'month': 'February'},
    {'year': 2020, 'month': 'March'},
    {'year': 2020, 'month': 'April'},
    {'year': 2021, 'month': 'January'},
    {'year': 2021, 'month': 'February'},
    {'year': 2021, 'month': 'March'},
    {'year': 2021, 'month': 'April'},
    {'year': 2022, 'month': 'January'},
    {'year': 2022, 'month': 'February'},
    {'year': 2022, 'month': 'March'},
    {'year': 2022, 'month': 'April'},
    {'year': 2023, 'month': 'January'},
    {'year': 2023, 'month': 'February'},
    {'year': 2023, 'month': 'March'},
    {'year': 2023, 'month': 'April'},
    {'year': 2024, 'month': 'January'},
    {'year': 2024, 'month': 'February'},
    {'year': 2024, 'month': 'March'},
    {'year': 2024, 'month': 'April'}
]
```
Your task is to write a function that groups the months by their respective years. The result should be an array of objects where each object represents a year, containing a `title` key (representing the year) and an `options` key. The `options` key should be an array of objects representing the months that belong to that year.

### Expected Output

```python
[
    {
        'title': 2019,
        'options': [
            {'year': 2019, 'month': 'January'},
            {'year': 2019, 'month': 'February'},
            {'year': 2019, 'month': 'March'},
            {'year': 2019, 'month': 'April'}
        ]
    },
    {
        'title': 2020,
        'options': [
            {'year': 2020, 'month': 'January'},
            {'year': 2020, 'month': 'February'},
            {'year': 2020, 'month': 'March'},
            {'year': 2020, 'month': 'April'}
        ]
    },
    {
        'title': 2021,
        'options': [
            {'year': 2021, 'month': 'January'},
            {'year': 2021, 'month': 'February'},
            {'year': 2021, 'month': 'March'},
            {'year': 2021, 'month': 'April'}
        ]
    },
    {
        'title': 2022,
        'options': [
            {'year': 2022, 'month': 'January'},
            {'year': 2022, 'month': 'February'},
            {'year': 2022, 'month': 'March'},
            {'year': 2022, 'month': 'April'}
        ]
    },
    {
        'title': 2023,
        'options': [
            {'year': 2023, 'month': 'January'},
            {'year': 2023, 'month': 'February'},
            {'year': 2023, 'month': 'March'},
            {'year': 2023, 'month': 'April'}
        ]
    },
    {
        'title': 2024,
        'options': [
            {'year': 2024, 'month': 'January'},
            {'year': 2024, 'month': 'February'},
            {'year': 2024, 'month': 'March'},
            {'year': 2024, 'month': 'April'}
        ]
    }
]
```


---

**Question 2:**

Modify the function so that only the first two years are grouped into their own object (each having a `title` key as their year). The remaining years should be grouped together under a single object with the title `others`.
### Expected Output

```python
[
    {
        'title': 2019,
        'options': [
            {'year': 2019, 'month': 'January'},
            {'year': 2019, 'month': 'February'},
            {'year': 2019, 'month': 'March'},
            {'year': 2019, 'month': 'April'}
        ]
    },
    {
        'title': 2020,
        'options': [
            {'year': 2020, 'month': 'January'},
            {'year': 2020, 'month': 'February'},
            {'year': 2020, 'month': 'March'},
            {'year': 2020, 'month': 'April'}
        ]
    },
    {
        'title': 'others',
        'options': [
            {'year': 2021, 'month': 'January'},
            {'year': 2021, 'month': 'February'},
            {'year': 2021, 'month': 'March'},
            {'year': 2021, 'month': 'April'},
            {'year': 2022, 'month': 'January'},
            {'year': 2022, 'month': 'February'},
            {'year': 2022, 'month': 'March'},
            {'year': 2022, 'month': 'April'},
            {'year': 2023, 'month': 'January'},
            {'year': 2023, 'month': 'February'},
            {'year': 2023, 'month': 'March'},
            {'year': 2023, 'month': 'April'},
            {'year': 2024, 'month': 'January'},
            {'year': 2024, 'month': 'February'},
            {'year': 2024, 'month': 'March'},
            {'year': 2024, 'month': 'April'}
        ]
    }
]
```
---
**Question 3:**

Given a square matrix, calculate the absolute difference between the sums of its diagonals.
For example, the square matrix arr is shown below:
```
1 2 3
4 5 6
9 8 9 
```

### Expected Output

The left-to-right diagonal = `1 + 5 + 9 = 15`. The right to left diagonal = `3 + 5 + 9 = 17`. Their absolute difference is `|15 - 17| = 2`.

---
**Question 4:**

This is a staircase of size n = 4.
```
   #
  ##
 ###
####
```

Its base and height are both equal to n. It is drawn using # symbols and spaces. The last line is not preceded by any spaces.

Write a program that prints a staircase of size n.

Output Format:

Print a staircase of size n using # symbols and spaces.

Note: The last line must have 0 spaces in it.

### Expected Output

Sample Input: 6

Sample Output:
```
     #
    ##
   ###
  ####
 #####
######
```
---

