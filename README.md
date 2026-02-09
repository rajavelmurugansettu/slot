# Ex02 Time Table
## Date: 07-02-2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<html>
    <head>
        <title>Time Table</title>
    </head>
    <body>
      <center>
        <img src="/static/logo.png" width="1050" height="200" >
        </center>
<table align="center" border="4" cellspacing="5" cellpadding="5">
<caption><B>SLOT TIME TABLE - RAJAVELMURUGAN S (25012404)</B></caption>
  <tr bgcolor="#FFFACA">
    <th>Day/Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
  </tr>
  <tr>
    <th bgcolor="#E8F0FD">8-10</th>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">FWAD</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Python</td>
    <td bgcolor="#A161E2">Python</td>
    <td bgcolor="#A161E2">CDS</td>
  </tr>
  <tr>
    <th bgcolor="#E8F0FD">10-12</th>
    <td bgcolor="#A161E2">FWAD</td>
    <td bgcolor="#A161E2">Python</td>
    <td bgcolor="#A161E2">FWAD</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Free</td>
  </tr>
  <tr>
    <th bgcolor="#E8F0FD">12-1</th>
    <td align="center" colspan="6"  bgcolor="#A161E2">LUNCH</td>
  </tr>
  <tr>
    <th bgcolor="#E8F0FD">1-3</th>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">MM</td>
    <td bgcolor="#A161E2">CDS</td>
    <td bgcolor="#A161E2">FWAD</td>
    <td bgcolor="#A161E2">FWAD</td>
  </tr>
  <tr>
    <th bgcolor="#E8F0FD">3-5</th>
    <td bgcolor="#A161E2">Python</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Free</td>
    <td bgcolor="#A161E2">Python</td>
  </tr>
</table>
<br>
<br>
<table align="center" cellspacing="5" cellpadding="5" border="4">
  <tr bgcolor="#E8F0FD">
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
  </tr>
  <tr bgcolor="#A161E2">
    <td>1.</td>
    <td>19AI414</td>
    <td>FUNDAMENTALS OF WEB DEVELOPMENT(FWAD)</td>
    </tr>
  <tr bgcolor="#A161E2">
    <td>2.</td>
    <td>19AI301</td>
    <td>PYTHON PROGRAMMING(Python)</td>
  </tr>
  <tr bgcolor="#A161E2">
    <td>3.</td>
    <td>19EY708</td>
    <td>CAREER DEVELOPMENT SKILLS(CDS)</td>
  </tr>
    <tr bgcolor="#A161E2">
    <td>3.</td>
    <td>ECA-M</td>
    <td>MENTOR MEET(MM)</td>
  </tr>
</table>
</body>
</html>


~~~

## OUTPUT
![alt text](<aizen/slotapp/static/Screenshot (18).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
