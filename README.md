Welcome file
Welcome file
# Common Chunks the one can use in online assignmnets

Hi! I'm krishank writing this file which has  **Common Chunks** of code which the once can use in online assignments


# TODO

- Write Metrix functions
- Write Medium Article

```  
  
  

// Distinict Count of value from an Array

// const myArray = ['a','b','c','a','c','a'];

// var result = {};

// myArray.forEach( x => result[x] = (result[x] || 0)+1 );

// console.log(result)

// // output { a: 3, b: 1, c: 2 }

  
  
  
  

//Distinict Value from an Array

// const myArray = ['a','b','c','a','c','a'];

// var result = myArray.filter((value, index, self)=> self.indexOf(value)===index)

// console.log(result)

  

// Output [ 'a', 'b', 'c' ]

  
  

// Add Remove value from an array from some position

// myArray.splice(numberOfValuesToBeremoved, fromWhichIndex, valuesToBeAdded)

  
  

// Find and replace a value from from array

// var items = [523, 3452, 334, 31, 5346];

// var index = items.indexOf(3452);

  

// if (~index) {

// items[index] = 1010;

// }

  
  

// Distinict values of an key in an Object

  

// var users = [

// {name: "Krishank", age:28},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Neha", age:40},

// {name: "Pawan", age:25}

// ]

// var result = [...new Set(users.map(x => x.name))]

// console.log(result)

  

// Output [ 'Krishank', 'Anuj', 'Neha', 'Pawan' ]

  
  

// Distinict Object from an Object

  

// var users = [

// {name: "Krishank", age:28},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Neha", age:40},

// {name: "Pawan", age:25}

// ]

// const result = [];

// const map = new Map();

// for (const item of users) {

// if(!map.has(item.age)){

// map.set(item.age, true); // set any value to Map

// result.push({

// age: item.age,

// name: item.name

// });

// }

// }

// console.log(result)

  

// Output

//[{ age: 28, name: 'Krishank' },

// { age: 27, name: 'Anuj' },

// { age: 40, name: 'Neha' },

// { age: 25, name: 'Pawan' }]
Common Chunks the one can use in online assignmnets
Hi! I’m krishank writing this file which has Common Chunks of code which the once can use in online assignments

TODO
Write Metrix functions
Write Medium Article
  
  

// Distinict Count of value from an Array

// const myArray = ['a','b','c','a','c','a'];

// var result = {};

// myArray.forEach( x => result[x] = (result[x] || 0)+1 );

// console.log(result)

// // output { a: 3, b: 1, c: 2 }

  
  
  
  

//Distinict Value from an Array

// const myArray = ['a','b','c','a','c','a'];

// var result = myArray.filter((value, index, self)=> self.indexOf(value)===index)

// console.log(result)

  

// Output [ 'a', 'b', 'c' ]

  
  

// Add Remove value from an array from some position

// myArray.splice(numberOfValuesToBeremoved, fromWhichIndex, valuesToBeAdded)

  
  

// Find and replace a value from from array

// var items = [523, 3452, 334, 31, 5346];

// var index = items.indexOf(3452);

  

// if (~index) {

// items[index] = 1010;

// }

  
  

// Distinict values of an key in an Object

  

// var users = [

// {name: "Krishank", age:28},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Neha", age:40},

// {name: "Pawan", age:25}

// ]

// var result = [...new Set(users.map(x => x.name))]

// console.log(result)

  

// Output [ 'Krishank', 'Anuj', 'Neha', 'Pawan' ]

  
  

// Distinict Object from an Object

  

// var users = [

// {name: "Krishank", age:28},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Anuj", age:27},

// {name: "Neha", age:40},

// {name: "Pawan", age:25}

// ]

// const result = [];

// const map = new Map();

// for (const item of users) {

// if(!map.has(item.age)){

// map.set(item.age, true); // set any value to Map

// result.push({

// age: item.age,

// name: item.name

// });

// }

// }

// console.log(result)

  

// Output

//[{ age: 28, name: 'Krishank' },

// { age: 27, name: 'Anuj' },

// { age: 40, name: 'Neha' },

// { age: 25, name: 'Pawan' }]
