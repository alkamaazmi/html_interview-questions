# HTML Interview Question

### [What is HTML](https://www.w3schools.com/html/html_intro.asp)

* HTML stands for Hyper Text Markup Language.
* HTML is the standard markup language for creating Web pages.
* HTML elements tell the browser how to display the content.
* HTML describes the structure of a Web page.

#### A Simple HTML Document
````html
<!DOCTYPE html>
<html>

<head>
<title>Page Title</title>
</head>

<body>
<h1>My First Heading</h1>
<p>My first paragraph.</p>
</body>

</html>

````
### Tag in HTML

* Tags are the starting and ending parts of an HTML element.
* Whatever written inside < and > are called tags.

### HTML elements

* HTML elements are defined by a starting tag, may contain some content and a closing tag.
* For example,`<h1> heading </h1>` is a HTML element.
 
 ### Void elements in HTML

 HTML elements which do not have closing tags, are Void element or Empty elements.

### [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)

HTML attributes provide additional information about HTML elements.

### How many types of heading does an HTML contain?

The HTML contains six types of headings. `<h1>` defines the most important heading and `<h6>` defines the least important heading.
`````
<h1>Heading no. 1</h1> 
<h2>Heading no. 2</h2>    
<h3>Heading no. 3</h3>    
<h4>Heading no. 4</h4>    
<h5>Heading no. 5</h5>    
<h6>Heading no. 6</h6>  
`````
### [HTML Entities](https://www.w3schools.com/html/html_entities.asp)

* An HTML entity is a piece of text that begins with an ampersand (&) and ends with a semicolon.

* Entities are used to display  reserved characters and invisible characters (like non-breaking spaces).

* Two words separated by a non-breaking space will stick together (not break into a new line).

### Block-level Elements

* Block-level elements start from a new line and consume the full width of the page available.

###  Inline and elements 

* Inline elements just take up the space that is absolutely necessary for the content and does not start from a new line.

### What are Semantic Elements?

* A semantic element clearly describes its meaning to both the browser and the developer.

* Non-semantic elements: `<div>` and `<span>`, Tells nothing about its content. While Semantic elements: `<form>` , `<table>` , Clearly defines its content.

### [HTML Links](https://www.w3schools.com/html/html_links.asp)

* HTML links are hyperlinks. You can click on a link and jump to another document.
* The HTML `<a>` tag defines a hyperlink. It has the following syntax:
```
<a href="url">link text</a>
```
* The most important attribute of the `<a>` element is the `href` attribute, which indicates the link's destination.

#### HTML Links - The target Attribute

* By default, the linked page will be displayed in the current browser window.
* The target attribute specifies where to open the linked document.
* The target attribute can have one of the following values:
   * _self - Default. Opens the document in the same window/tab as it was clicked
   * _blank - Opens the document in a new window or tab
   * _parent - Opens the document in the parent frame
   * _top - Opens the document in the full body of the window

````
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
````

### [HTML Images](https://www.w3schools.com/html/html_images.asp)

* The HTML `<img>` tag is used to embed an image in a web page.
* The <img> tag has two required attributes:
  * src - Specifies the path to the image
  * alt - Specifies an alternate text for the image
```
<img src="url" alt="alternatetext">
````

#### Image as a Link

To use an image as a link, put the `<img>` tag inside the `<a>` tag :

````
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
````
### [HTML Lists](https://www.w3schools.com/html/html_lists.asp)

* HTML lists allow web developers to group a set of related items in lists.

* Unordered HTML List:

  * The list items will be marked with bullets(small black circles) by default:
  ````
  <ul>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
  </ul>
  `````
* Ordered HTML List
  
  * The list items will be marked with numbers by default:
  ````
  <ol>
   <li>Coffee</li>
   <li>Tea</li>
   <li>Milk</li>
  </ol>
  ````
* HTML Description Lists

   * A description list is a list of terms, with a description of each term.
   ```
    <dl>
       <dt>Coffee</dt>
       <dd>- black hot drink</dd>
       <dt>Milk</dt>
       <dd>- white cold drink</dd>
    </dl>

   ````

### [HTML Tables](https://www.w3schools.com/html/html_tables.asp)

HTML tables allow web developers to arrange data into rows and columns.

````html
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

`````
### Note :
* The `<caption>` tag defines a table caption or title. The `<caption>` tag must be inserted immediately after the `<table>` tag.

* HTML `<colgroup>` element defines a group of columns within a table.

* The `<col>` HTML element defines a column within a table and is used for defining common semantics on all common cells. It is generally found within a `<colgroup>` element.

* `colspan` attribute is used to specify the number of columns that a cell should span horizontally.

* `rowspan` attribute is used to specify the number of rows that a cell should span vertically.

### The `class` attribute :

The `class` attribute is used to specify the class(es) to which an HTML element belongs. Multiple HTML elements can share the same class. You can assign multiple classes to an element by separating them with spaces. In CSS, you can style an element based on its class by using the "." selector followed by the name of the class.

### The `id` attribute :
In HTML, the "id" attribute is used to specify a unique identifier for an HTML element. You cannot have more than one element with the same id in an HTML document.In CSS, you can style an element based on its "id" by using the "#" selector followed by the "id" name. 

### `iframe` :

An HTML `iframe` is used to display a web page within a web page.
````html
<iframe src="/default.asp" width="100%" height="300">
</iframe>
````

### HTML Forms

* An HTML form is used to collect user input. The user input is most often sent to a server for processing.

* The HTML `<form>` element is used to create an HTML form for user input.

##### HTML `<input>` Tag

* The `<input>` tag specifies an input field where the user can enter data.
* The `<input>` element can be displayed in several ways, depending on the type attribute.
* The different input types are as follows:

* `<input type="button">`
* `<input type="checkbox">`
* `<input type="date">`
* `<input type="email">`
* `<input type="number">`
* `<input type="password">`
* `<input type="radio">`
* `<input type="submit">`

##### The `<label>` Element:

* The `<label>` tag defines a label for many form elements.

* The `for` attribute of the `<label>` tag should be equal to the `id` attribute of the `<input>` element to bind them together.

* The `<label>` element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox.

##### The `name` Attribute for `<input>`

* Each input field must have a name attribute to be submitted.

* If the `name` attribute is omitted, the value of the input field will not be sent at all.

##### The `<select>` Element :

* The `<select>` element defines a drop-down list.
``` html
<label for="cars">Choose a car:</label>
<select id="cars" name="cars" size="4" multiple>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>

`````

##### The `<textarea>` Element

* The `<textarea>` element defines a multi-line input field 

`````html
<textarea name="message" rows="10" cols="30">
 The cat was playing in the garden.
</textarea>
`````

##### The `<fieldset>` and `<legend>` Elements

* The `<fieldset>` element is used to group related data in a form.

* The `<legend>` element defines a caption for the `<fieldset>` element.

````html
<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>
`````

#### Farewell Party Survey Form

````html
<form action="">

        <label for="fname">First Name</label>
        <input type="text" name="fname" id="fname" placeholder="Enter your first name"><br>

        <label for="lname">Last Name</label>
        <input type="text" name="lname" id="lname" placeholder="Enter your last name"><br>

        <label for="age">Age</label>
        <input type="number" name="age" id="age" placeholder="Enter your Age"><br>

        <label for="email">Email</label>
        <input type="text" name="email" id="email" placeholder="Enter your email"><br>

        <label for="password">Password</label>
        <input type="password" name="password" id="password" placeholder="Enter your password"><br>

        <label>Gender</label>
        <input type="radio" name="gender" id="gender1"  value="male"> <label for="gender1">Male</label>
        <input type="radio" name="gender" id="gender2" value="female"> <label for="gender2"  >Female</label>
        <input type="radio" name="gender" id="gender3" value="other"> <label for="gender3">Other</label><br>
        
        <label for="role">Which option best describes you?</label>
          <select name="role" id="role">
            <option value="student">Student</option>
            <option value="intern">Intern</option>
            <option value="professional">Professional</option>
            <option value="other">Other</option>
          </select><br>

          <label>What did you like about the program?</label><br>
          <input type="checkbox" id="v1" name="v1" value="Training">
          <label for="v1">Training</label><br>
          <input type="checkbox" id="v2" name="v2" value="Community">
          <label for="v2">Community</label><br>
          <input type="checkbox" id="v3" name="v3" value="Food">
          <label for="v3">Food</label><br>

          <label for="comment">Any Comments</label>
          <textarea name="comment" id="comment" cols="30" rows="10" placeholder="Enter Some Comments"></textarea><br>
         
          <button type="reset" value="reset" id="reset">
            Reset
          </button>
          <button type="submit" value="submit" id="submit">
            Submit
          </button>


    </form>

`````

