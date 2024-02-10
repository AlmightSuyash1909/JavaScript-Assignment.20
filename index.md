   #### For each code snippet given below check if it's valid or not. Explain with your reason.
1.

```js
function add(let a = 0, let b = 0){
  return a + b;
}

add(21, 23);
```
- What is the output of the above code write error if invalid? // error
- Is the code above valid or not? // invalid
- Explain the reason


2.

```js
function add(a = 0; b = 0) {
  return a + b;
}

add(21, 23);
```
- What is the output of the above code write error if invalid? // 44
- Is the code above valid or not? // valid
- Explain the reason

3.

```js
function add(a = 0, b) {
  return a + b;
}
add(21);
```
- What is the output of the above code write error if invalid? // NaN
- Is the code above valid or not? // valid
- Explain the reason

4.

```js
function add(a = 0, b = 0) {
  return a + b;
}

add(undefined, 21);
```
- What is the output of the above code write error if invalid? // 21
- Is the code above valid or not? // valid
- Explain the reason

5.

```js
function knowWhy(value) {
 return if(value === 21){
      console.log("Yes");
    } else {
     console.log("No");
    }
}
knowWhy(211);
```
- What is the output of the above code write error if invalid? // error
- Is the code above valid or not? // invalid
- Explain the reason

6.

```js
function knowWhy(value) {
 return value
}
knowWhy(for(){});
```
- What is the output of the above code write error if invalid? // error
- Is the code above valid or not? // invalid
- Explain the reason

7.

```js
function isItIf(ifElse) {
  return ifElse;
}
isItIf(if(true){console.log('Testing')});
```
- What is the output of the above code write error if invalid? // error
- Is the code above valid or not? // invalid
- Explain the reason

8.

```js
function add(a = 0, b = 0) {
  return a + b;
}

add(null, 21);
```
- What is the output of the above code write error if invalid? // 21
- Is the code above valid or not? // valid
- Explain the reason 