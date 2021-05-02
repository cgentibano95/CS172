# CS172 - Assignment 1 (Tokenization)

## Team member 1 - Christopher Gentibano


Language used: Python
parsing.py takees care of tokenization and creates a large dictionary that then gets passed into read_index.py.

Tokenizaton occurs in parsing.py, position is saved, termid is saved, and the docno all passed into a tuple

In the "index_dictionary" it takes in "word" as a key, and the value will be the token tuple. So every word will essentially have a tuple, and multiple tuples if it is found more than once.


Read_index takes care of term and doc commands to count total terms and also lists number of docs containing the term as requested.

it'd be taken like the following:
```bash
python read_index.py -- term despicable
```
Or any of the following examples used in the assignment description works as well!
