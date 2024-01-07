# Amazon Dataset Analysis
## Overview

This project utilizes a dataset obtained from [Stanford SNAP](http://snap.stanford.edu/data/amazon0302.html). The goal is to implement various graph algorithms, including BFS Distance, Strongly Connected Components, and Pagerank, on the provided dataset.

## Video Presentation

Check out our project presentation on YouTube: [Project Demo](https://youtu.be/rfwqpG2OFBs)

## Building the Code

1. **Create Build Directory:**
    ```bash
    mkdir build
    ```

2. **Navigate to Build Directory:**
    ```bash
    cd build
    ```

3. **CMake and Make:**
    ```bash
    cmake ..
    make
    ```

## Running the Code

1. **Choose Algorithms:**
    - In the `main.cpp` file, set the boolean variables to `true` for the algorithms you want to run.

2. **Compile and Run:**
    - After building, use the following commands in the terminal:
        ```bash
        ./test/
        ```

## Troubleshooting

1. **Changing Input Data Path:**
    - Update the test data paths in the `tests/tests.cpp` file by modifying the relevant variables.

2. **Adjusting Algorithm Variables:**
    - In the `main.cpp` file, update the algorithm-specific variables to point to the correct input data paths.

## Files Used for Each Function

### BFS Distance Algorithm
- `main.cpp`: Function for Amazon test data.
- `tests.cpp`: Test cases (`testpr2`, `testpr3`, `test_data`).

### Strongly Connected Algorithm
- `main.cpp`: Test data.
- `tests.cpp`: Test cases (`testpr2`, `testpr3`, `test_data`).

### Pagerank Algorithm
- `main.cpp`: Function for Amazon test data.
- `tests.cpp`: Test cases (`testpr1`, `testpr2`, `testpr3`).

### Adjacency List
- `main.cpp`: Function for Amazon test data.
- `tests.cpp`: Test cases (`testpr1`, `test_data`).

