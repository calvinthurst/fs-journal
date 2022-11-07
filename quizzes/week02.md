# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let var and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a subprogram designed to preform specific tasks
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsibility principle,open closed principle,liskov substitution principle,interface segregation principle,dependency inversion principle.they are principle that help you get into the habit of writing cleaner code that will easy to be maintained or improved upon in the future
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
[2] because you start the count at 0
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
let friend = (i=> i.friends == [])
friend.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
function doThis(isConditional) {
  return (isConditional ? 'true' : 'false');
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
initializer i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
 document object model html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
null,undefined,boolean,number,bigint,string,symbol,objects and arrays
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
arguments are the values of parameters
parameters are the names that are used to define a function
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values cant be changed without creating and entirely new value
```