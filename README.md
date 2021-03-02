# frontend Interview Question


- ✨JAVASCRIPT ✨

## JAVASCRIPT

## 1. create a function which will increase the counter by one

It is example of IIFE, for better understand you can explore these links

- [link 1](https://stackoverflow.com/questions/35237779/difference-between-an-iife-and-non-iife-in-javascript-modular-approach)
- [link 2](www.w3schools.com/js/js_function_closures.asp)

```
const addOne = (function(){
  let counter = 0;
  return () => {
	return counter += 1;
  }
})();

addOne() // will return incremental counter


**## 2. What are mutable and immutable types in JavaScript?**
**Mutable** objects are objects **whose value can change once created**, 
while **immutable** objects are those** whose value cannot change once created**. 

In JavaScript :- 

	**numbers**, **strings**, **null**, **undefined** and **Booleans** are primitive types which are **immutable**. 
	**Objects**, **arrays**, **functions**, **classes**, **maps**, and **sets** are **mutable**.
