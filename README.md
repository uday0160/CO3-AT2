# Railway Reservation Search and Government Analytics Platform

## Project Overview

This repository contains implementations of searching and sorting algorithms based on real-world case studies. The project demonstrates the application of Divide and Conquer techniques in data processing systems.

The repository includes:

1. Railway Reservation Search System using Binary Search
2. Government Analytics Platform using Merge Sort and Quick Sort

---

# Question 1: Railway Reservation Search System Using Binary Search

## Problem Description

A railway reservation database contains sorted train schedules and booking records. Searching a specific train record efficiently is required for quick access by staff and passengers.

## Algorithm Used

Binary Search

## Concept

Binary Search follows the Divide and Conquer approach. It repeatedly divides the sorted dataset into two halves and searches the required element efficiently.

## Input

- Number of train records
- Sorted train numbers
- Train number to search

## Output

- Position of train record if found
- Record not found message if unavailable

## Complexity Analysis

Time Complexity:

Best Case: O(1)

Average Case: O(log n)

Worst Case: O(log n)

Space Complexity:

O(1)

## File Structure

Question_1/

- Source_Code/
  - binary_search.c

- Output_Screenshots/

- Report/

---

# Question 2: Government Analytics Platform Using Merge Sort and Quick Sort

## Problem Description

A government analytics system processes large datasets for policy reports and demographic analysis. Efficient sorting methods are required to organize large amounts of data.

## Algorithms Used

1. Merge Sort
2. Quick Sort

## Concept

Both algorithms use the Divide and Conquer technique.

Merge Sort divides data into smaller parts and merges them after sorting.

Quick Sort selects a pivot and partitions data around the pivot element.

## Input

- Number of records
- Dataset values

## Output

- Sorted data using Merge Sort
- Sorted data using Quick Sort

## Complexity Analysis

### Merge Sort

Best Case: O(n log n)

Average Case: O(n log n)

Worst Case: O(n log n)

Space Complexity: O(n)


### Quick Sort

Best Case: O(n log n)

Average Case: O(n log n)

Worst Case: O(n²)

Space Complexity: O(log n)

---

# Comparison

| Feature | Merge Sort | Quick Sort |
|---|---|---|
| Method | Divide and Conquer | Divide and Conquer |
| Speed | Consistent | Faster in practice |
| Memory | More memory required | Less memory required |
| Stability | Stable | Not stable |
| Large Dataset | Suitable | Suitable with optimization |

---

# Repository Structure
