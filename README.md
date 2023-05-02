Download Link: https://assignmentchef.com/product/solved-coen79-lab-4
<br>
<h1>§ Sub-project 1:<strong> Keyed Bag </strong></h1>




Another way to store a collection of items is in a <strong>keyed bag</strong>. In this type of bag, whenever an item is added, the programmer using the bag also provides an integer called the key.




To this end, two arrays are used:




key_type keys[CAPACITY];    // The array to store the keys         value_type data[CAPACITY];  // The array to store items







Each item added to the keyed bag must have a unique key; two items cannot have the same key. So, the insertion function has the specification shown here:




void keyed_bag::insert (const value_type&amp; entry, int key);

// Precondition: size( ) &lt; CAPACITY, and the bag does not yet contain any

// item with the given key.

// Postcondition: A new copy of entry has been added to the bag, with the // given key.




When the programmer wants to remove an item from a keyed bag, the key of the item must be specified, rather than the item itself. The keyed bag should also have a boolean member function that can be used to determine whether the bag has an item with a specified key.




<strong>For this project, do a complete specification, design, and implementation of a keyed bag. </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h1>§ Sub-project 2:<strong> Polynomials </strong></h1>

<strong> </strong>

<strong>For the second project, specify, design, and implement a class for polynomials. </strong>

A polynomial is an arithmetic expression of the form:

a<sub>” </sub>+ a<sub>$</sub>x + a<sup>&amp;</sup>x<sub>&amp;</sub>




The highest exponent, k , is called the degree  of the polynomial, and the constants are the coefficients.




The class may contain a static member constant, MAXDEGREE, which indicates the maximum degree of any polynomial. (This allows you to store the coefficients in an array with a fixed size.) Spend some time thinking about operations that make sense on polynomials. For example, you can write an operation that adds two polynomials. Another operation should evaluate the polynomial for a given value of x.




You may add additional functions to the header files if you wish to write more to help you complete the assignment. You may NOT alter the names or structure of any of the







functions or attributes that are already within the header files. If you do add your own functions, make sure to update the header file’s comments to discuss those functions’ preconditions and postconditions. You will also be required to include an invariant in each of the implementation files that you write.


