# frontend Interview Question


- ✨JAVASCRIPT ✨

## JAVASCRIPT

- create a function which will increase the counter by one
- 

It is example of IIFE, for better understand you can explore these links

```
const addOne = (function(){
  let counter = 0
  return () => {
	return counter += 1
  }
})()
addOne() // will return incremental counter
