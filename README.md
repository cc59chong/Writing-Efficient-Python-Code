# Writing-Efficient-Python-Code
## Discription

### Chapters 1 Foundations for efficiencies
In this chapter, you'll learn what it means to write efficient Python code. You'll explore Python's Standard Library, learn about NumPy arrays, and practice using some of Python's built-in tools. This chapter builds a foundation for the concepts covered ahead.
* `range()`, `*range()`(unpack a range), `enumerate()`, `*enumerate()`, `map()`, `*map()`(unpack map into a list), `np.arange()`, `.reshape()`
### Chapters 2 Timing and profiling code
In this chapter, you will learn how to gather and compare runtimes between different coding approaches. You'll practice using the line_profiler and memory_profiler packages to profile your code base and spot bottlenecks. Then, you'll put your learnings to practice by replacing these bottlenecks with efficient Python code.
* `%timeit`: setting the number of runs(`-r`) and/or loops(`-n`), saving the output to a variable (`-o`)
* `.timings`: the time for each run, `.best`: the best time for all runs, `.worst`: the worst time for all runs
* `%%timeit`
* **runtime**:`line_profiler`(package), `%load_ext line_profiler`, `%lprun -f`
* **memory**: `memory_profiler`(package), `%load_ext memory_profiler`, `%mprun -f`
### Chapter 3 Gaining efficiencies
This chapter covers more complex efficiency tips and tricks. You'll learn a few useful built-in modules for writing efficient code and practice using set theory. You'll then learn about looping patterns in Python and how to make them more efficient.
* `zip()`
* `collections`(module): `Counter()`
* `itertools`(module): 'combinations()`
* `set`: `intersection()`, `.difference()`, `.symmetric_difference()`, `.union()`
* `np.sum()`, `np.mean()`
### Chapter 4 Basic pandas optimizations
This chapter offers a brief introduction on how to efficiently work with pandas DataFrames. You'll learn the various options you have for iterating over a DataFrame. Then, you'll learn how to efficiently apply functions to data stored in a DataFrame.
* `.iterrows()`, `.itertuples()`, `.apply()`+`lambda`, `.values` (array approach) <br>
***Using NumPy arrays was the fastest approach, followed by the .itertuples() approach, and the .apply() approach was slowest.***
