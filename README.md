# List of numbers on Recamán's sequence


## What is this?

This repo contains a list of a lot of numbers of Recamán's sequence. The sequence is computed using the following rules:

* start at 0
* your jump distance increases by 1 every iteration
* jump down if you can:
	* the number you would jump down hasn't already been visited
	* and the number is greater than 0
* else you jump up

This results in the following sequence:
0, 1, 3, 6, 2, 7, 13, 20, 12, 21, 11, 22, 10, 23, ...


## links

* Check out this brillant video about the sequence from **Numberphile**: https://youtu.be/FGC5TdIiT9U
* see also: https://oeis.org/A005132
* and: https://en.wikipedia.org/wiki/Recam%C3%A1n%27s_sequence

the internet is full of nice visualisations of this:
https://www.instagram.com/p/BzAqUL_nfoP/?utm_source=ig_web_copy_link


## some facts

If you calculate the first 1k numbers of the sequence, you still won't have visited the number 19. You will also have missed 61, 76, 133 and a lot of others. The number 19 is only visited after 99735 iterations.

After 100k iterations the smallest missing number is 1355. You will find that it isn't even in my list of the first 100 million numbers. It's also missing from the list of the first 500 million nubmers because 1355 only appears at iteration 325.374.625.245 (see https://oeis.org/A057167/b057167.txt).


## Why?

Yeah, don't ask. I guess this counts as a hobby of some sort.
Does anyone really need this - I think not.
