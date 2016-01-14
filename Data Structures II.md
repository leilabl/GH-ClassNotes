# DATA STRUCTURES II

## Dictionary ADT 

AKA Associative Array, Map, Symbol Table

Store key-value pairs

Hash tables - how the compiler implements the data structure

Array to hold values and a hash function that tranforms a string key into a numerical index

```function hash (keyString) {
	var hashed = 0;
	for (var i = 0; i <keyString.length; i++) {
	hashed += keyString.charCodeAt(i);
	}
	return hashed % 12; //# of spaces in array (fixed)
}```

this converts string into a number

Example 12 bucket array

Store the name Grace at index 0
Store the phone number 111-111-1111 at index 8

