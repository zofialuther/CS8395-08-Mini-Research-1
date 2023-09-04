# Generative AI Coding Abilities Benchmark: Optimizing for the Halstead Difficulty Metric

## Introduction

Welcome to the Generative AI Coding Abilities Benchmark. This assignment comprises 100 distinct coding problems tailored to assess the mathematical coding abilities of your Generative AI system. The focus of this benchmark is measure maintained robustness when optimizing solutions for the Halstead Difficulty Metric, which is a measure of code complexity and readability.

## Halstead Difficulty Metric

The Halstead Difficulty Metric (D) is computed using the formula:

`D = (n1/2) * (N2/n2)`


Where:
- `n1` denotes the number of distinct operators
- `n2` denotes the number of distinct operands
- `N2` denotes the total occurrences of operands
- `D` quantifies the code's understanding difficulty

Optimizing for the Halstead Difficulty Metric underscores the significance of producing code solutions that balance correctness with readability and maintainability.

## Problem Solving

All coding problems are stored in the `problems.json` file within this repository. Each entry contains a unique problem UUID, a problem description, and an explanation of the sample input and output. Your task is to harness your Generative AI system's capabilities to generate solutions that achieve correctness.

## How to Run the Benchmark

1. Develop solutions for each problem contained in the `problems.json` file, leveraging your Generative AI system's coding abilities. The solution must have a `solve` function that takes in the proper input and returns a single numeric output.
2. Ensure the solutions are optimized for correctness while adhering to the provided sample input and output explanations for each problem.
3. To evaluate the correctness of the solution, run the evaluate_program function located in the evaluation.py file. This will report the percentage of total tests passed for that coding program.

## Evaluation

Solutions will be evaluated solely based on correctness. Each problem solution is assessed against the provided test input and output cases to validate accuracy.

## Results and Insights

The intention is to combine the results of this benchmark with other developed test suites to conduct an in-depth analysis of generative AI's coding abilities. This analysis will illuminate the capabilities of Generative AI in producing accurate and correct code solutions that align with the given sample input and output explanations.

Embark on this Generative AI Coding Abilities Benchmark to ascertain the proficiency of your system in generating accurate coding solutions. 🚀🧮
