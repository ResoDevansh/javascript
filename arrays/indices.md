# Indices

So you have your array of data elements, but what if you want to access a specific element? This is where indices come in. An **index** refers to a spot in the array. Indices logically progress one by one, but it should be noted that the first index in an array is 0, as it is in most languages. Brackets [] are used to signify you are referring to an index of an array.

```javascript
// This is an array of strings
var fruits = ["apple", "banana", "pineapple", "strawberry"];

// We set the variable banana to the value of the second element of
// the fruits array. Remember that indices start at 0, so 1 is the
// second element. Variable banana now has "banana" stored in it.
var banana = fruits[1];
```


Define the variables using the indices of the array

 **GivenInfo**

var cars = ["Mazda", "Honda", "Chevy", "Ford"]

var honda =?

var ford =?

var chevy =?

var mazda =?


 **Solution**
 
var cars = ["Mazda", "Honda", "Chevy", "Ford"]

var honda = cars[1];

var ford = cars[3];

var chevy = cars[2];

var mazda = cars[0];

**Validation**

assert(honda === "Honda");

assert(ford === "Ford");

assert(chevy === "Chevy");

assert(mazda === "Mazda");

*Meet you in the next file.*
