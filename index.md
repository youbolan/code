## Useful Code



### Copy text out from html dropdown.

First, use develper tool to get the elementID. Then run the code in console.

```javascript
var t; 
t = "";
document.getElementById('[elementId]').innerText.split('\n').forEach( (element) => {t = t + element + '\n'}); 
console.log(t);

```


