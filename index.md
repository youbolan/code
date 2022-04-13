## Useful Code

You can use the [editor on GitHub](https://github.com/youbolan/code/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Copy elements out from html dropdown.

First, use develper tool to get the elementID. Then run the code in console.

```javascript
var t; t = "";
document.getElementById('u81_input').innerText.split('\n').forEach( (element) => {console.log(element); t = t + element + '\n'}); 
console.log(t);

```

-
