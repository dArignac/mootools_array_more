Additional Functions for the Array class
===========

Provides additional functions on arrays.
Currently available functions are:

intersect(array): creates an intersection of the current array and the given one.
differentiate(array): returns the symmetric difference between this array and the given one.
getRange(int, int): Returns the given number of elements from the array starting at the given index.

How to use
----------

Simply include the javascript file after including MooTools core.

Then use them:

	var a = [1, 2, 3, 4, 5];
	var b = [4, 5, 6, 7, 8];
	
	a.intersect(b);
	// returns [4, 5]
	
	a.differntiate(b);
	// returns [1, 2, 3, 6, 7, 8]
	
	a.getRange(2, 3);
	// return [3, 4, 5]
