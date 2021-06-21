# Tests For Matiasevich Solver

This repository contains test and results for Matiasevich word equations solver

Tests were parsed from SMT-format using parser developed by [Antonina Nepeivoda](https://github.com/TonitaN)

Original tests in SMT-format could be found [here](https://www.informatik.uni-kiel.de/~mku/woorpje/#_benchmarks)

Matiasevich solver was also tested with custom benchmark developed by [Antonina Nepeivoda](https://github.com/TonitaN)

### Testing results:


| Benchmark        | Number of tests  | Solved Standard | Cycled Standard | Solved Finite | Cycled Finite | Solved Z3      | Cycled Z3       |
| ---------------- |:----------------:|:---------------:|:---------------:|:-------------:|:-------------:|:--------------:|----------------:|
| First            | 200              |  200            | 0               | 200           | 0             |  190           | 10              | 
| Second           | 9                |   9             | 0               | 9             | 0             |  3             | 6               | 
| Third            | 200              |                 |
| Fifth            | 200              |  198            | 2               | 200           | 0             |  177           | 23              | 
| Custom           | 50               |  45             | 5               | 46            | 4             |  30            | 20              | 
