Math_Histogram
==============

These classes can be used to calculate histogram distributions
of data sets. It assumes that data has no nulls.

The Math_Histogram class computes histograms and associated statistics
from unidimensional data sets. These are also known as 2D histograms, 
and can be computed using the regular binned frequency or as cummulative 
frequency.

Similarly, the Math_Histogram3D and Math_Histogram4D classes compute
distributions from bi- and tri-dimensional data sets (respectively),
both in regular frequency and cummulative frequency modes.

This package requires the Math_Stats package, so if you do not have it
installed, you need to do:

	$ pear install Math_Stats

before you can start using Math_Histogram in your scripts.

This is old code I wrote for [PEAR](http://pear.php.net). 
Originally it was tracked in CVS, then it was moved to SVN, 
and now I am importing it to git :-)

-- Jesus M. Castagnetto
