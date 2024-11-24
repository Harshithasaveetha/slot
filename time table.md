# Ex03 Time Table
## Date:19/11/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```<html>
<head>
<title>time table</title>
</head>
<body>
    <table>'
        <style>
             table,th,td{border:2px solid black;
            border-collapse:collapse;}
        </style>
        <tr>
            <td>day</td>
            <td>8am to 10am</td>
            <td>10am to 12pm</td>
            <td>1pm to 3pm</td>
            <td>3pm to 5pm</td>
        </tr>
        <tr>
        <td>MONDAY</td>
        <td></td>
        <td>WEB</td>
        <td></td>
        <td></td>
        </tr>
        <tr>
        <td>Tuesday</td>
        <td>BEEE</td>
        <td>DE</td>
        <td>python</td>
        <td></td>
        </tr>
        <tr>
        <td>Wednesday</td>
        <td></td>
        <td>BEEE</td>
        <td></td>
        <td></td>
        </tr>
        <tr>
        <td>Thursday</td>
        <td></td>
        <td>python</td>
        <td>WEB</td>
        <td></td>
        </tr>
        <tr>
        <td>Friday</td>
        <td></td>
        <td>DE</td>
        <td>python</td>
        <td></td>
        </tr>
        <tr>
        <td>Saturday</td>
        <td></td>
        <td>CDS</td>
        <td>python</td>
        <td>WEB</td>
        </tr>
    </table><br>
    <table>
        <style>
            table,th,td{border:2px solid black;border-collapse: collapse;}
        </style>
        <tr>
            <td>slot number</td>
            <td>subject</td>
        </tr>
        <tr>
            <td>19AI301C</td>
            <td>Python and Linear algebra</td>
        </tr>
        <tr>
            <td>19AI414</td>
            <td>Fundamentals of web application</td>
        </tr>
        <tr>
            <td>19EE305</td>
            <td>BEEE</td>
        </tr>
        <tr>
            <td>19EE404</td>
            <td>Digital electronics</td>
        </tr>
        <tr>
            <td>19EY708</td>
            <td>Career Development skills</td>
        </tr>
        </table>
        </body>
        </html>
```
## OUTPUT
![alt text](<Screenshot (32).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
