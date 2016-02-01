# switchingtabs
While surfing the internet, I've noticed while changing from one to another tab, that the title of the page (or window) could change. It looks difficult but in fact it is something very easy. <br/><br/>
How do you do it? 
With Javascript off course! <br/>You only need 2 lines of code to come to the result. <br/>I've added an example in 'home.html' to see it live in action!

<p>when you are gone</p>
```javascript
window.onfocus = function () { 
document.title = 'Welcome'; 
}
```

<p> when you are on the page</p>
```javascript
window.onblur = function () {
document.title = 'Come back!';
}
```
