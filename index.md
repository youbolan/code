## Useful Code



### Copy elements out from html dropdown.

First, use develper tool to get the elementID. Then run the code in console.

```javascript
var t; t = "";
document.getElementById('u81_input').innerText.split('\n').forEach( (element) => {console.log(element); t = t + element + '\n'}); 
console.log(t);

```

-
