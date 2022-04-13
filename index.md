## Useful Code



### Copy text out from html dropdown.

First, use develper tool to get the elementId. Then run the code in console. Repleace [elementId] with the real elementId.

```javascript
var t = ""; 
document.getElementById('[elementId]').innerText.split('\n').forEach( (element) => {t = t + element + '\n'}); 
console.log(t);

```


