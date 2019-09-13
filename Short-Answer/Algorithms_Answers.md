#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n)
As n increases linearaly so to does the run time. For instance if n = 1 the loop would only run 1 time, for n = 3 the loop would run three times, at n = 100 the loop would run 100 times


b)O(n log n)
According to my unserstandment a simple why of looking at n log n is N loops that are logarithmic. Because J is mutiplied by 2 each time you are basicly going to ever run half of n meaning the while loop is logarithmic and the while loop will be repeated N times by the for loop


c)O(n) 
This function is recursive and as the input gets bigger so does the time it takes to compute, I would also
argue that it is O(n!) as while it doesn't multiply a number by n - 1 of it self like a factorial would it 
still grows juss ad fast.

## Exercise II

The best solution to finding the tallest floor you could "drop/throw" an egg from would be divide and conqure. More importantly we know that the top floors are proably never going to be considered so we can fessibly forget about them.

Recursivly we could divide the building in half and always test the lower half until the egg stops breaking and then once the egg is "safe" at which point we could test the floors going back up till the egg breaks again.


