# Writing-Efficient-Python-Code
## Discription

### Chapters 1 Foundations for efficiencies
In this chapter, you'll learn what it means to write efficient Python code. You'll explore Python's Standard Library, learn about NumPy arrays, and practice using some of Python's built-in tools. This chapter builds a foundation for the concepts covered ahead.
* `range()`, `*range()`(unpack a range), `enumerate()`, `*enumerate()`, `map()`, `*map()`(unpack map into a list), `np.arange()`, `.reshape()`

and 2 

### Chapter 3 
### Chapter 4 Basic pandas optimizations
This chapter offers a brief introduction on how to efficiently work with pandas DataFrames. You'll learn the various options you have for iterating over a DataFrame. Then, you'll learn how to efficiently apply functions to data stored in a DataFrame.
* `.iterrows()`, `.itertuples()`, `.apply()`+`lambda`, `.values` (array approach) <br>
***Using NumPy arrays was the fastest approach, followed by the .itertuples() approach, and the .apply() approach was slowest.***
