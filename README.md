# JavaScript Syntax Guide

This JS Syntax Guide will cover:
- Comments
- Loops
- Variables
- Objects
- Functions & Parametres 
- Arrays
- Data Types
- Boolean Statements
- Comparison Statements

| **Comments** |
Comments aid in creating readable, explainable & function code that works with readers for issues or concerns
Comments are made in the .js file using a backslash.
`/* a comment */`


| **Loops** |
Loops are blocks of code based on conditions that perform without having to be called. 
Types of Loops: - While, - If & Else, - For
**While Loop**
While is declared, followed by the conditional statement (true or false) followed by the code action.
`While ()
console.log`

**If & Else Loop**
If is declared followed by a *true* condition for code action within curly brackets. Else is declared with the false condition within curly brackets.
`if () {
}else{
}`

**For Loop**
For is declared followed by the conditional statement then the code action with curly brackets
`for (){
  console.log()
}`

| **Variables** |
Variables can be assigned values that are stored. JS uses var, let, const
```
var size = "medium"
let color = "blue"
const clothing = "shirt"
```
let is abled to be declared again as it is blocked-scoped
`let shirt = 15`
var is globally scoped & cannot be used more than once. The same is for const though it's block-scoped
`const clothing = "shirt"
const clothing = "trousers"  /* this will return an error */`

|**Arrays**|
Arrays are another way to store data- they are variables that contain multiple variables. 
Arrays are definded by [] with variables separated by a comma
`const outfit = ['jeans', 'sweater', 'shoes'];`
Arrays also contain different datatypes
`const outfit = [1, 2, false, 'jeans'];`

|**Data Types**|
The types of data stored as value in JS that can be assigned to variables
- Boolean: true or false 
- String: "string" number: 16 
- null: a variable with nothing in it 
- undefined: a variable that is explicitly defined as undefined, an unassigned value
```
let style = null  : null data type
var blue = true : Boolean data type
let size = 8 : number data type ** numbers do not need to be contained by ' ' 
const trousers = "cotton" : string data type** strings must be contained by " "/ ' '
```
|**Objects**|
Objects are a more complete data storage system. Objects can contain collections of different data types.


