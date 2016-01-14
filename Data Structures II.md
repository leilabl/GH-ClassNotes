# DATA STRUCTURES II

## Dictionary ADT 

AKA Associative Array, Map, Symbol Table

Store key-value pairs

#Hash Tables
- how the compiler implements the data structure

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

###Collisions
Store email - email is passed to the hash function that yelds index 8
That bucket is already full

- Open address - if a bucket is full look at the next empty bucket
- Separate chaining - precede buckets with another data structure - linked list add a new node to the bucket

##Storing key-value pairs

###Association Lists

###Store an Array

###Store an Object (Struct)
node.value.key
node.value.value

##Hash tables are better than one big linked list

- performance: faster access to data


#Trees

Most important data structure - often implement and traverse

upside-down - 

primary root node

each node is the root of it's own tree

levels, depth

childless nodes are trees

##Binary Trees
where each node has between 0 and 2 children
###Binary Search Tree
K
any values that are less than K will be stored to the left
if value === K, at discretion

	 __K__
	|     |
  __D__   G
 |     |  |
 A     G  Q

 Search minimum value:
 looks to the left / cuts half of tree
 efficient search

 logarithmic time

 left child value < root value <= right child value

 ###How to implement:
 - array - algebraic
 K,L,A,F,null,R
 0,1,2,3,4,5,6

