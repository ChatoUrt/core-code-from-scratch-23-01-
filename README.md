# core-code-from-scratch-23-01-

## ---"This"---

* [Test](https://www.codewars.com/kata/547c71fdc5b2b38db1000098/train/javascript)

Solution 1 / /

``` javascript
function NameMe(first, last) { 
  this.firstName = first;
  this.lastName = last;
  this.name = this.firstName + ' ' + this.lastName;
}
```

Solution 2 / /

``` javascript
function NameMe(first, last) { 
  this.firstName = first;
  this.lastName = last;
  this.name = first + ' ' + last;
}
```

---
## ---Knowledge Base---
[This - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/this)
