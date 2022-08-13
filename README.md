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
```

## 2. What are mutable and immutable types in JavaScript?
**Mutable** objects are objects **whose value can change once created**, <br/>
while **immutable** objects are those **whose value cannot change once created**. 

In JavaScript :- 
```
**numbers**, **strings**, **null**, **undefined** and **Booleans** are primitive types which are **immutable**. <br />
**Objects**, **arrays**, **functions**, **classes**, **maps**, and **sets** are **mutable**.
```

## 3. How to handle Callback hell?

One of the options are async/await and Promise

```
const makeBurger = async () => {
  const beef = await getBeef();
  const cookedBeef = await cookBeef(beef);
  const buns = await getBuns();
  const burger = await putBeefBetweenBuns(cookedBeef, buns);
  return burger;
};

// Make and serve burger
makeBurger().then(serve);
```
with error handling

```
const summerActivities = async () => {
  try {
    const result = await fightTheDemogorgon();
    const seasonsLeft = await rollForDamage(result);
    const finalResult = await closeTheGateIn(seasonsLeft);
    console.log('Hawkins is safe for ' + finalResult + ' more seasons.'));
  } catch (e) {
    failureCallback();
  }
}

```
## 4. What is Functional Programming?

Functional programming rules :-

1. Keep your data and function totaly separate.

```
let score = 100;

function addBonus(){
 score = score + 10;
 return score;
}

v/s

// functional approach =>

function addBonus( score ) {
 return score + 10;
}

later function is functional programming approach. Benefits for this 

1. It is testable
2. It is not dependent on global variable.
3. Self in take function.


2. don't update same variable again.

```

## 5. what are synthetic event in React?
## 6. dynamic vs static typing typescript
## 7. custom  hook pattern react
## 8. what is microservices?
## 9. micro frontend vs monolith
## 10. react HOC patterns
## 11. useref react
## 12. usecallback react
## 13. functional programming vs oop
## 14. functional programming core concepts
## 15. what is the output of the following program?
var x = "asdf zxcv";
x[1] = "h";
console.log(x[1]);

## 16. 	what will be the output?
async function foo() {
	return 1
}



## 17. what will be the output? 
var x = { a: 1, b: 2};
var y = x;
y.a = 42;
delete y.b

console.log(x.a, x.b)



