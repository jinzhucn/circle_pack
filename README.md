circle_pack
===========

We are interested in the following problem: given the collection of critical
values of a rational map (of the Riemann sphere), and the monodromy around
these branch points, to recover the coefficients of the rational map (up to
precomposition with a Mobius transformation). 

One approach is to get an initial estimate via circle packing, and then to
use Newton's method to adjust the coefficients. At the moment, this program
implements simple circle packing (works OK for ~1000 circles; accurate, but
not super fast). Taking (combinatorial) branched covers is implemented,
but buggy. 
