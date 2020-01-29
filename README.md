# List of numbers of Recamán's sequence


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

<p align="center">
  <img src="https://user-images.githubusercontent.com/28928394/73361337-0e967580-42a5-11ea-913c-cf8c9f5cf5d6.png" alt="recamanFirst 100" width="60%">
</p>


## some facts

If you calculate the first 1k numbers of the sequence, you still won't have visited the number 19. You will also have missed 61, 76, 133 and a lot of others. The number 19 is only visited after 99735 iterations.

After 100k iterations the smallest missing number is 1355. You will find that it isn't even in my list of the first 100 million numbers. It's also missing from the list of the first 500 million nubmers because 1355 only appears at iteration 325.374.625.245 (see https://oeis.org/A057167/b057167.txt).


## Why?

Yeah, don't ask. I guess this counts as a hobby of some sort.

Does anyone really need this? - I think not.

-----

Plotted visualisation inspired by⁣ Alex Bellos and Edmund Harriss:
<p align="center">
  <img src="https://user-images.githubusercontent.com/28928394/73362026-5ff33480-42a6-11ea-860d-9f75c9aa715b.jpg" alt="recaman visualisatoin" width="90%">
</p>



## links

* Check out this brillant video about the sequence from **Numberphile**: https://youtu.be/FGC5TdIiT9U
* see also: https://oeis.org/A005132
* and: https://en.wikipedia.org/wiki/Recam%C3%A1n%27s_sequence


-----


<p align="center">
  <img src="https://user-images.githubusercontent.com/28928394/73360579-86fc3700-42a3-11ea-9cc0-6f1ec45eed8a.png" alt="recaman first 1k" width="70%">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/28928394/73361447-42719b00-42a5-11ea-9b92-6c45ac460d6c.png" alt="recaman first 100 million" width="100%">
</p>
