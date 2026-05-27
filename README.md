# Design and Analysis of Algorithms — Python Implementations

A collection of classic algorithm implementations in Python, with empirical performance analysis.

## Algorithms Implemented

| File | Algorithm | Concept |
|------|-----------|---------|
| file_handling.py | File I/O with Exception Handling | Error handling, file operations |
| string_search.py | Substring Search | String manipulation |
| csv_search.py | CSV Parsing & Pattern Matching | File processing |
| matrix_operations.py | 2D Matrix Traversal | Arrays, indexing |
| kmp_lps.py | KMP — LPS Table Construction | Pattern preprocessing |
| kmp_search.py | KMP Pattern Matching | String searching O(n+m) |
| sort_comparison.py | Insertion Sort vs Merge Sort | Empirical time & comparison analysis |
| search_comparison.py | Naive Search vs KMP | Performance benchmarking |

## Key Highlights
- **Empirical Analysis**: Sort and search algorithms benchmarked on 1000 random integers
- **Performance Comparison**: Time taken and number of comparisons recorded for each algorithm
- **KMP Implementation**: Full KMP with LPS table built from scratch

## Tech Stack
- Python 3
- Built-in libraries: `time`, `csv`, `random`, `sys`

## How to Run
```bash
# Clone the repo
git clone https://github.com/Nitharsana-1/DAA_Assignment.git
cd DAA_Assignment

# Run any file
python sort_comparison.py
python search_comparison.py
```

## Sample Output — Sort Comparison
```
Empirical Comparison: Insertion vs Merge Sort
Insertion Sort - Time: 0.00312 seconds, Comparisons: 247891
Merge Sort     - Time: 0.00089 seconds, Comparisons: 8714
```
