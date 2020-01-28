#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n log n)


b) O(n^2)


c) O(n)

## Exercise II

For every 'egg' thrown off of 'f' floor, check the current number of sotries.

If higher than 'f' floor, don't thrown the 'egg', else thrown the 'egg'.

<!--psuedo code -->
curr_story = 0

def find_f(floors):
    for egg in list of floors
    check curr_story
        if curr_story > floors
        dont throw egg
    else:
        throw egg

Time Complexity = O(n)  n = number of floors
