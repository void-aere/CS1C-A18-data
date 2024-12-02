# WARNING
The sorted data is not correct. I'm working on it now.

## How to test with presorted data

In your driver, after loading the input file from disk, run a sequential verification that it's sorted. (If any value is greater than the one that follows it, the list is unsorted.) If that check succeeds, you can bypass the sorting step.
