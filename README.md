# WARNING
The sorted data is not correct. I'm working on it now.

UPDATE: 
1,000,000 is the only dataset not yet fixed. It will be uploaded in about 20 minutes. The rest are good to go.

## How to test with presorted data

In your driver, after loading the input file from disk, run a sequential verification that it's sorted. (If any value is greater than the one that follows it, the list is unsorted.) If that check succeeds, you can bypass the sorting step.
