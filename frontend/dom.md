## Accessing an element by id


```javaScript
document.getElementById("idName");
```
## Writing values to a tag
```javaScript
document.getElementById("idName").innerHTML
```
## Accessing value of a form
```javaScript
document.getElementById("idName").value
```
## Create element in memory 
```javaScript
const y=document.createElement("div");
```
## append this element to dom
```javaScript
const z=document.getElementById("idName");
z.appendChild(y)