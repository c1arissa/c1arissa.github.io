### To Do List:
- [-] Sticky footer (header?)
- [-] Resume image - formatting, etc.
- [-] Little Home button

Sticky Footer

```
<!DOCTYPE html>
<html>
<head>
<style>
.footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: red;
   color: white;
   text-align: center;
}
</style>
</head>

<body>

<div class="footer">
  <p>Footer</p>
</div>

</body>
</html> 
```

Vertical Line:

```
<!DOCTYPE html>
<html>
<head>
<style>
.vl {
    border-left: 6px solid green;
    height: 500px;
    position: absolute;
    left: 50%;
    margin-left: -3px;
    top: 0;
}
</style>
</head>
<body>

<h2>Vertical Line</h2>

<div class="vl"></div>

</body>
</html>
```

Grids:

```
<!DOCTYPE html>
<html>
<head>
<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
}

/* Create three equal columns that floats next to each other */
.column {
    float: left;
    width: 33.33%;
    padding: 10px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}
</style>
</head>
<body>

<h2>Three Equal Columns</h2>

<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#ccc;">
    <h2>Column 3</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>
```

#### Centered Text And Images In Github Markdown

Normal Text

<p align="center">
  <b>Some Links:</b><br>
  <a href="#">Link 1</a> |
  <a href="#">Link 2</a> |
  <a href="#">Link 3</a>
  <br><br>
  <img src="http://s.4cdn.org/image/title/105.gif">
</p>

Normal text

:blue_heart:
:green_heart:
:frog:
:octocat:
:octopus:

`![Alt text](/path/to/img.jpg)`

```
<span class="fa-stack" style="font-size:14px;">
  <i class="fa fa-circle-thin fa-stack-2x" style="color:#9b4dca;"></i>
  <i class="fa fa-twitter fa-stack-1x"></i>
</span>
```
