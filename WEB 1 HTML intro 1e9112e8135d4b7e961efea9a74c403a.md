# WEB 1. HTML intro

## **HTML tags**

# HEADING

```html
<h1> WEBTECH </h1>
<h2> WEBTECH </h2>
<h3> WEBTECH </h3>
```

# paragraph

```html
<p> paragraph </p>
```

# insert image

```html
<img src="pic_trulli.jpg" alt="Italian Trulli">

```

# html file path

| Path | Description |
| --- | --- |
| <img src="picture.jpg"> | The "picture.jpg" file is located in the same folder as the current page |
| <img src="images/picture.jpg"> | The "picture.jpg" file is located in the images folder in the current folder |
| <img src="/images/picture.jpg"> | The "picture.jpg" file is located in the images folder at the root of the current web |
| <img src="../picture.jpg"> | The "picture.jpg" file is located in the folder one level up from the current folder |

# image mapping

[https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d8424.876438376179!2d38.75201220453525!3d9.039475405652329!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b8f69f9c910bb%3A0xf3b5e05243ab160f!2sPiassa!5e0!3m2!1sen!2set!4v1700292246035!5m2!1sen!2set](https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d8424.876438376179!2d38.75201220453525!3d9.039475405652329!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b8f69f9c910bb%3A0xf3b5e05243ab160f!2sPiassa!5e0!3m2!1sen!2set!4v1700292246035!5m2!1sen!2set)

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d8424.876438376179!2d38.75201220453525!3d9.039475405652329!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b8f69f9c910bb%3A0xf3b5e05243ab160f!2sPiassa!5e0!3m2!1sen!2set!4v1700292246035!5m2!1sen!2set" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```

# DIVISION

```html
<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>
```

# list tags

```html
<ul>
   <li> rolex </li>
   <li> rolex </li>
</ul>

<ol>
   <li> patek </li>
    <li> patek </li>
</ol>
```

# html table

```html
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

# html ID

```html
<h2 id="C4">Chapter 4</h2>
```

# html class

```html
<h2 class="city main">London</h2>
```

# html Forms

form element 

```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

<input> element

| Type | Description |
| --- | --- |
| <input type="text"> | Displays a single-line text input field |
| <input type="radio"> | Displays a radio button (for selecting one of many choices) |
| <input type="checkbox"> | Displays a checkbox (for selecting zero or more of many choices) |
| <input type="submit"> | Displays a submit button (for submitting the form) |
| <input type="button"> | Displays a clickable button |

# coloring

```html
<p style="background-color;tomato;">color</p>
```