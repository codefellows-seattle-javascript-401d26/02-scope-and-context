# Quiz
### 

Write the questions and answers for the quiz in the corresponding 'You Don't Know JS: Scope & Closures' chapter.

##### Chapter 01 - What is scope? 

````
// Code
function foo(a) {
  var b = a;
  return a + b;
}

var c = foo( 2 );
````
1. Identify all the LHS look-ups (there are 3!).

- (a) implicit declare 
- var b =; 
- var c =;

2. Identify all the RHS look-ups (there are 4!).

- foo(2)
- = a
- (a)
- b

