
# Lab 02: HTML Basics

## Introduction:
HTML is the standard markup language for creating web pages and web applications. During lectures, students have learned the structure of an HTML document and basic HTML tags. In this lab, students will practice the basic HTML tags.
## Lab Objectives:
The objective of this lab is to help students in building a single page website using basic HTML tags.  Students will apply the basic HTML tags such as tables, links, lists etc. to create single page web site.
## Tools:
Dreamweaver, notepad, browser.
## Helping Material:
* W3Schools: https://www.w3schools.com/html/default.asp 
* HTML Links: https://www.w3schools.com/html/html_links.asp 
* HTML Lists: https://www.w3schools.com/html/html_lists.asp
* HTML Tables: https://www.w3schools.com/html/html_tables.asp 
 


### Lab Task 1:
 
Lists are important tags to display text in a list format. Get yourself familiarized with the basic concepts of lists (link is given above) and create an HTML page similar to the one given below:

#### CODE:
```
<!DOCTYPE html>
<html>
<head>
<title>Lists</title>
</head>
<body>
  <h1>Lists and Hyperlinks</h1>
  <p>There are two types of lists in HTML:</p>
  <ol>
    <li>Ordered List.</li>
    <li>Unordered List.</li>
  </ol>
  <p>This is an ordered list</p>
  <ol>
    <li>Toyota</li>
    <li>Honda</li>
    <li>Ferrari</li>
    <li>lamborghini</li>
    <li>Mercedes</li>
  </ol>
  <p>This is an Unordered list</p>
  <ul>
    <li>Biryani</li>
    <li>Chicken Palao</li>
    <li>Mutton Nihari</li>
    <li>Fish</li>
    <li>Cutlets</li>
  </ul>
  <p>This is a nested unordered list of links:</p>
  <ul>
    <li>Online Validator:</li>
    <ul>
      <li>
        <p>W3C Online HTML Validator @
          <a href="https://validator.w3.org/">https://validator.w3.org/</a>
        .</p>
      </li>
      <li>
        <p>W3C Online CSS Validator @
          <a href="https://jigsaw.w3.org/css-validator/">https://jigsaw.w3.org/css-validator/</a>
        .</p>
      </li>
    </ul>
      <li>Specifications:</li>
      <ul>
        <li>
          <p>HTML5 @
            <a href="https://www.w3.org/TR/html52/">https://www.w3.org/TR/html52/</a>
          .</p>
        </li>
        <li>
          <p>CSS3 Selectors @
            <a href="https://www.w3.org/TR/selectors-3/">https://www.w3.org/TR/selectors-3/</a>
          .</p>
        </li>
    </ul>

</body>
</html>
```
![alt text](https://i.ibb.co/cwyDCJs/2.png)

### Lab Task 2:
 
In HTML, it is possible to display text in tables and for this purpose <table> tag is used. Get yourself familiarized with the basic concepts of tables (link is given above) and create an HTML page which is showing your semester schedule in tabular format. An example is given below:

#### CODE:
```
<!DOCTYPE html>
<html>
<head>
<title>Tables</title>
<style>
table, th, td {
border: 1px solid black;
}
</style>
</head>
<body>
<h1>My Schedule</h1>
<table style="width:25%">
  <tr>
    <th>Subject</th>
    <th>Day</th>
    <th>Time</th>
    <th>Instructor</th>
  </tr>
  <tr>
    <td>CAO</td>
    <td>Monday</td>
    <td>9:00-10:00</td>
    <td>Imran Abeel</td>
  </tr>
  <tr>
    <td>CAO</td>
    <td>Tuesday</td>
    <td>10:00-11:00</td>
    <td>Imran Abeel</td>
  </tr>
  <tr>
    <td>CAO</td>
    <td>Wednesday</td>
    <td>14:00-15:00</td>
    <td>Imran Abeel</td>
  </tr>
  <tr>
    <td>WE</td>
    <td>Wednesday</td>
    <td>9:00-10:00</td>
    <td>Mujtaba Haider</td>
  </tr>
  <tr>
    <td>WE</td>
    <td>Thursday</td>
    <td>9:00-10:00</td>
    <td>Mujtaba Haider</td>
  </tr>
  <tr>
    <td>WE</td>
    <td>Friday</td>
    <td>9:00-10:00</td>
    <td>Mujtaba Haider</td>
  </tr>
</table>
</body>
</html>

```
![alt text](https://i.ibb.co/p0WKCnj/1.png)
