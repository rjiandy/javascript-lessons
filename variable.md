# Variable & Primitives

## data types
Data types in javascript:
1. Array = `[]` or `new Array()`
2. string = `""` or `''` or backticks \`
3. number = `123`
4. Object = `{ id: 123 }` (key, value pairs) 
5. function = `function setUser(params) {}` or `(params) => {}`

## Variable definition in javascript

There are 3 common type where we can define variables:
1. `var` = old javascript, can be found on php and lots of other programming language, can be mutable (re assign value)
2. `const` = this variable definition is immutable which means it cannot be re assigned
3. `let` = this is very similar to var but only differs in scoping (always use this for re-assignable value)

Example of variables definition and combined with primitives

`const username = 'john';`
`let username = 'john';`
`const playerList = ['john', 'stevan'];`
```
  // object example
  const user = {
    id: '123',
    name: 'john'
  };
```
```
  function setUserName(name) {
    // do something about username
  }
```
```
  // arrow function can be assigned to variable
  const setUserName = (name) => {
    // do something about username
  }
```

```
  const username = 'john'
  username = 'johny' // this will not work because const is not re-assignable
```


