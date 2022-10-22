# Patika_dev_Merge_Sort_Project

[Patika.dev](https://app.patika.dev/batuhangr)
-----

[16,21,11,8,12,22] -> Merge Sort

### 1. Write the stages of the above array according to the sort type. 

> We continue by dividing the sequence in binary states one by one until all numbers are left alone.

- [16,21,11,8,12,22]<p>
- [16,21,11] - [8,12,22]<p>
- [16] - [21,11] - [8] - [12,22]<p>
- [16] - [21] - [11] - [8] - [12] - [22]<p>

> After the division operations, we proceed by adding the array until it returns to its original state.

- [16] - [21,11] - [8] - [12,22]<p>
- [11,16,21] - [8,12,22]<p>
- [8,11,12,16,21,22]<p>

### 2. Write the Big-O notation.

O(nlogn)

-Worst Case: O(nlogn) -Average Case: O(nlogn) -Best Case: O(n*logn)
