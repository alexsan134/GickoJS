<div align="center"><img src="https://raw.githubusercontent.com/alexsan134/GickoJS/master/img/bns.png" width="500"></div>
<br>
<div align="justify"><h3>JS Library, with the most usually tools in your project, like String to Int convertions, array operations, async functions, promises, callbacks, ES6 implementation, HTTP request, AJAX, data convertions, data parsers, JSON, responsive design, dom manipulation, etc.</h3></div>

## We have 1ms per loop vs 5ms per loop for jQuery

<div align="center"><h1>Instalation</h1></div>

```
npm i geckojs
```
--------------

<dl>
  <dt><h2>Features:</h2></dt>
  <dd>* All data convertions (String, Array, Number, Object)</dd>
  <dd>* Most fasted selectors for the elements like querySelectors()</dd>
  <dd>* Easily structure (not write more do less lol)</dd>
</dl>

-------------
<div align="center"><h1>Documentation</h1></div>
<div align="left"><h3>Selectors:</h3></div>

Base form:

```javascript
g("yourElement").event("yourEvent", () =>{
  //Do something ...
  
})
```

You can select what element you want:

```javascript
//If you want only one element of a list with classes

var number = 2;
g("class", number).event("yourEvent", () =>{
  //Do something ...
  
})
```

And you can select a range of a list with elements

```javascript
//If you want to select a range: from first element to 3th element with '.class'

var limiter = 3;
g(".class").event("yourEvent", () =>{
  //Do something ...
  
}, limiter);
```
