# DATA STRUCTURES

## 1. Information Theory and Hardware

smaller piece of information - bit

phylosophy - bit is idea of truth

1800's I - true 0 -> false

1930's - mechanical, electrical switches
logic gates 
true - on
false - off

transistor - individual switch
equivalent to neuron

one laptop - 1.4 billion switches

tape drives - sequential access of data

late 80's - magnectic hard drives bacome popular

allows for jumping through the data, fast writting

solid state drive - SSD

hard memory - large size - slow access, blocking

ram - volatile - quick access - smaller space - stores date while powered

CPU - logical
L1 cache
L2 cache
L3 cache

fastest - CPU register

64 bits - more precision with math


## 2. Abstraction and Encoding

8 bits can represent any interger between 0 and 255 through {0,1} and positional notation

arabic writes right to left
number least significant at RIGHT - most signicant LEFT

??binary read right to left??

###IEEE 754

64 bits - 
one bit is arbitrarily the sign (negative or positive)

52 bits - store the number
11 bits - exponent notation - floating point (bicimal point)

NaN value is stored as number in IEEE 754
- typeof NaN > 'number'
- typeof Infinity > 'number'
- typeof -0 > 'number'
- typeof (1/0) > 'number'

issue of precision

binary is fractional - 

if need precision - download precision Math library or use another language - e.g. python

hexadacimal - easy to convert to binary

in CSS:
css notation: '#FFFFFF'
hexadecimal: 15, 15, 15
binary: 11111111,11111111,11111111

every letter has a different code
just like morse code

###ASCII
first popular encoding system
by Bell telephone company
7 bit unsigned - 8 bites - 128 characters
0011 0000 - 0
0011 0001 - 1
0011 0007 - 7

ghost bit created lots of problems - 

###Unicode UTF-8
flexible - variable width - can use more than one Code Unit bite to store value
backwards compatible

###Unicode UTF-16
incompatible


##Images

sequence of triplets - different brightness levels
3 bites per pixel

###Audio

PCM encoding - amplitude

## 3. APIs
operations - register, operations
Grace Hopper - first compiler - source code into machine code

hardware > operating system > object code > source code

## 4. Data Types and Data Structures
compiler - slower, but optimized result
interpreter - V8 engine e.g., javascript is not super fast - executes as it goes - not optimized

contiguous data structure vs linked data structure

###ADT vs DS 
Abstract data type - descriptions of information - human idea

Data Structures - real

Example:
Stack ADT
Collection of elements
ordered
elements can repeat (not a set)
- make a new stack
- add element (push)
- retrieve (pop) - LIFO (last in first out)

JS has 7 primitive data types

Undefined ( default for unassigned vars/ nonexistent props)
Null (typeof is wrong! Null is a primitive, not 'object')
Boolean
String (Immutable, but reasignable - create new space in memory - old assignment is being garbage collected)

Non-primitive
Objects
- mutable
- properties

Queue ADT
FIFO

Linked list DS
uses nodes - memory + address in memory

Head node
tail node

head node points to next node
add node in between
Number (64 bit signed float)
Symbol (ES6)
