📘 JavaScript Arrays

Arrays are ordered collections of values. They allow storing multiple items in a single variable.

🔹 1. Creating Arrays

They store values in a variable.

let fruits = ["apple", "banana"];

🔹 2. Accessing Elements

They use index to get items (starts at 0).

fruits[0]; // "apple"

🔹 3. Modifying Arrays

They add, remove, or change elements.

fruits.push("mango");  // add at end
fruits[1] = "orange";  // change value

🔹 4. Common Methods

The are useful built-in functions:

push() / pop() – add/remove last

shift() / unshift() – add/remove first

slice() – copy part

splice() – remove/replace

map() – transform

filter() – select elements

reduce() – combine elements

🔹 5. Iterating Arrays

Loop over each item.

fruits.forEach(f => console.log(f));
for (let f of fruits) console.log(f);

🔹 6. Multi-dimensional Arrays
Thy are arrays of arrays for grid-like structures.

let matrix = [[1,2],[3,4]];
matrix[1][0]; // 3

🔹 7. Spread Operator

They copy or merge arrays easily.

let copy = [...fruits];
let merged = [...fruits, "kiwi"];
