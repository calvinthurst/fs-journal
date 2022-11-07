# JavaScript
add script tag at the bottom of the html so the javascript to load in last
different data types 
<!-- primitive data types --> 
<!-- examples -->
let string = "hello"
let number = 4
let number = 5.694308
let bool = true or false
let dontknow = undefined // unknown nothing,
let nothing = null // known nothing

<!-- reference types this is a link to values -->
<!-- examples -->
<!-- arrays stores info by position -->
let strArr = ["howdy", 'hello', 'whats up']
let numArr = [3, 5, 6]
let mixArr = ['5', 10, 'sup']  <!-- try to avoid mixed type arrays it is bad practice -->
arrays store info by position 
<!-- objects -->
let obj = {
  key: 'value',
  name: 'mick',
  costume: 'Mega-mind',
} <!-- objects have dot notation and they also dont have order inside stores info by KEY VALUE so if you have something that needs info to be in order use an array -->

<!-- function  -->
<!-- example -->
function dosomething() {
  console.log('i did something')
}<!-- to get this data type to work you have to invoke it -->


<!-- THIS IS A CONCEPT FOR THE FUTURE -->
let funky = funtion(){
  console.log('this is a funky way to do it')
}<!-- this is a funky way to write a function  -->

function returnSomething(){
  return 'returned' <!-- returns value from funtions to where the function was called -->
}
function sum(){
  return 5 + 10 
}
<!-- you can only add strings together and when you add a number to a string it converts the number into a string -->
to run the a function in your html
<!-- real app begins below -->

let secretCode = '8432'

let yourCode = ''

function ghost(){
  yourCode += '8'
  console.log(ghost())
  <!-- good practice is testing in devtools to see if it works -->
}
<!-- if you are changing data console.log() the data -->

