# A Replication of The Log of Gravity

Santos Silva and Tenreyro wasn’t just an influential article, it defined my interest in gravity models to the point I wrote a master’s thesis on it for UN ESCAP. Here I replicate the main results from the original article in R.

Here I replicate the main results from @silva2006log in R. The original
results were obtained in [TSP](https://en.wikipedia.org/wiki/TSP_(econometrics_software))
back in 2006. Thanks to Joao Santos Silva for pointing that out, in a previous
commit of this repository I mentioned that it was done in Stata.

The idea here is to be explicit regarding the conceptual approach to regression in R. For most of the replication I used base R without external libraries (i.e packages) except when it was absolutely necessary. 
Much of the methods exposed here lead to the exact same results as using the gravity package which provides convenient wrappers for gravity estimation.

All questions are welcome to the address m.sepulveda@mail.utoronto.ca.

These notes were written with 
[varsityblues](https://github.com/pachadotdev/varsityblues).

## References

Santos Silva, Joao, and Silvana Tenreyro. “The Log of Gravity.” The Review of Economics
and Statistics 88, no. 4 (2006): 641–58.
