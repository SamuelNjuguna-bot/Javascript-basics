There are two ways of including javascript in html.


-internal javascript


-external javascript


internal javascript
In internal javascript the script code is embeded inside the head section of the html also it


can be included inside the body section. However its recomended that the latter method is most appropriate. 


when icluding the file in the body section, a doper element should be placed. This ensures the javascript is loaded


```
<script src="learningJavascript.js" defer></script>
```


```javascript
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
<h1>Internal Javascript</h1>
    <script>
 let name = "learning_javascript"
 console.log(name)
    </script>
  </body>
</html>
```


Output


```
console.log("learning_javascript")
```


External JavaScript


In external javascript the code snippet that is the javascript is hacked in a separate folder then like we link 


css to html, we adopt a simmilar technique .


```javascript
   <!doctype html>
 <html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="externalJavascript.js"></script>
  </head>
  <body>
    <h1>External Javascript </h1>
  </body>
</html>
```

```
externalJavascript.js


<script>
 let name = "learning_javascript"
 console.log(name)
</script>
 ```


 Output


```
console.log("learning_javascript")
```


