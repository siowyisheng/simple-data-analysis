# The Simple Guide to Data Analysis with Python

_Data Analysis with Python explained simply._

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/siowyisheng/simple-data-analysis/blob/master/LICENSE) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## Table of Contents <!-- omit in toc -->

- [What is Data Analysis?](#what-is-data-analysis)
- [What does Data Analysis look like?](#what-does-data-analysis-look-like)
  - [How do I get the last n rows of a DataFrame?](#how-do-i-get-the-last-n-rows-of-a-dataframe)
  - [How do I get the rows of a DataFrame starting from row i to j?](#how-do-i-get-the-rows-of-a-dataframe-starting-from-row-i-to-j)
  - [How do I add multiple columns to a DataFrame simultaneously?](#how-do-i-add-multiple-columns-to-a-dataframe-simultaneously)
  - [How do I create a 1d array?](#how-do-i-create-a-1d-array)
  - [How do I create a 2d array?](#how-do-i-create-a-2d-array)
  - [How do I create a 1d array of random numbers from 0 to 1?](#how-do-i-create-a-1d-array-of-random-numbers-from-0-to-1)
  - [How do I perform operations on all the values of an array?](#how-do-i-perform-operations-on-all-the-values-of-an-array)
  - [How do I get the nth column or row of data in an array?](#how-do-i-get-the-nth-column-or-row-of-data-in-an-array)

## What is Data Analysis?

## What does Data Analysis look like?

### How do I get the last n rows of a DataFrame?

```python
df.tail(10)
```

### How do I get the rows of a DataFrame starting from row i to j?

```python
df.iloc[i:j]
```

### How do I add multiple columns to a DataFrame simultaneously?

```python
df.assign(
    **{
        'newcol_1': 'some default',
        'newcol_2': 'some default',
        'newcol_3': 'some default',
    }
)
```

Create the dict above programmatically.

### How do I create a 1d array?

```python
np.array([1,2,3,4,5])
np.arange(0,10)
```

### How do I create a 2d array?

```python
np.array([1,2,3,4,5],[6,7,8,9,10])
np.arange(0,10)
```

### How do I create a 1d array of random numbers from 0 to 1?

```python
np.random.rand(10)  # generates a 1d array of 10 elements
```

### How do I perform operations on all the values of an array?

```python
arr + 5
arr - 5
arr * 5
arr / 5
```

### How do I get the nth column or row of data in an array?

```python
arr[0, :]  # first column
arr[:, 0]  # first row
```
