# sorting_rs
## This library contains following sorting algorithms implemented in Rust:
 
| Sorting algorithm | Features and downsides | Worst-case performance O(): comparisons; swaps | Best-case performance O(): comparisons; swaps | Space complexity O() |
| ------ | -------------------------------- | ------------------------------------ | -------- | ---------- |
| Bubble | bad for sorted or reversed input | `n`<sup>`2`</sup>; `n`<sup>`2`</sup> | `n`; `1` | `n` or `1` |
| Cocktail | little performance improvement over bubble sort | `n`<sup>`2`</sup> | `n` | `1` |
| Comb | speeds up when data is nearly sorted | `n`<sup>`2`</sup> | `nlogn` | `1` |
| Gnome | simple and slow, works with one item at a time | `n`<sup>`2`</sup> | `n` | `1` |
| Heap | independent of data distribution | `nlogn` | `nlogn` or `n` | `n` or `1` |
| Bottom-up Heap | upgraded version of heapsort with decreased number of comparisons | `nlogn` | `nlogn` or `n` | `n` or `1` |
| Insertion | simple, but less effective than quicksort, heapsort or merge sort | `n`<sup>`2`</sup>; `n`<sup>`2`</sup> | `n`; `1` | `n` or `1` |
| Merge | independent of data distribution | `nlogn` | `nlogn` or `n` | `n` |
| Odd-even | presented to be effective on processors with local interconnections | `n`<sup>`2`</sup> | `n` | `1` |
| Odd-even (Batcher) | more efficient version of odd-even sort | `log`<sup>`2`</sup>`n` | `log`<sup>`2`</sup>`n` | `log`<sup>`2`</sup>`n` |
| Quick | bad for sorted or reversed input | `n`<sup>`2`</sup> | `n` | `n` or `logn` |
| Selection | the least number of swaps among all the algorithms | `n`<sup>`2`</sup>; `n` | `n`<sup>`2`</sup>; `1` | `1` |
| Shell | it is optimization of insertion sort | `n`<sup>`2`</sup> or `nlog`<sup>`2`</sup>`n` | `nlogn` or `nlog`<sup>`2`</sup>`n` | `n` |
| Slow | it's slow, who would ever need it? | | | |
| Smooth | variant of heapsort, good for nearly sorted data | `nlogn` | `n` | `n` or `1` |
| Stooge | it's a bit faster than slow sort | `n`<sup>`2.7095`</sup> | | `n` |