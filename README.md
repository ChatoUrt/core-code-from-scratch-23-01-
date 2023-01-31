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
## ---Sumando indices del array, dentro de un array---

* [Test](https://www.codewars.com/kata/586e1d458cb711f0a800033b/train/javascript)

Solution / /

``` javascript
function processData(data) {
  let total = 1;
  for(let i = 0; i < data.length; i++){
    let result = data[i][0] - data[i][1];
    total *= result;
  }
  return total;
}
```

---
## ---Stop gninnipS sdroW---

* [Test](https://www.codewars.com/kata/5264d2b162488dc400000001/train/javascript)

Solution / /
```javascript
function spinWords(words) {
  let arr = words.split(' ');
  for (let i = 0; i < arr.length; i++) {
    if (arr[i].length >= 5) {
      arr[i] = arr[i].split('').reverse().join('');
     }
  }
  return arr.join(' ');
}
```

---
## ---Knowledge Base---
[This - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/this)
