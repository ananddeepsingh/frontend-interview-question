# frontend Interview Question


- ✨JAVASCRIPT ✨

## JAVASCRIPT

- create a function which will increase the counter by one

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
