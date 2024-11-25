# Ex03 Time Table
## Date:25/11/2024

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
    <body>
        <img src="c:\Users\admin\Downloads\sec logo.png">
         <table border="1" cellspacing="15" cellpadding="2">
            <caption>Timetable-Harshitha-24900600</caption>
            
            <center>
            <tr bgcolor="blue">
                <th>Day/Time</th>
                <th>Mon</th>
                <th>Tues</th>
                <th>Wed</th>
                <th>Thu</th>
                <th>Fri</th>
                <th>Sat</th>
            </tr>
            <tr>
                <td bgcolor="orange">8 - 10</td>
                <td bgcolor="yellow colspan="2">Free slot</td>
                <td>Free slot</td>
                <td>python</td>
                <td>phy</td>
                <td>web</td>
                <td>eng</td>
            </tr>
            <tr>
                <td>10 - 12</td>
                <td>python</td>
                <td>edm</td>
                <td>eng</td>
                <td>cds</td>
                <td>mat</td>
                <td>phy</td>

            </tr>
            <tr>
                <td>12 - 1</td>
                <td colspan="6">lunch</td>
            </tr>
            <tr>
                <td>1 - 3</td>
                <td>web</td>
                <td>web</td>
                <td>Mentor</td>
                <td>Free slot</td>
                <td>edm</td>
                <td>mat</td>
            </tr>
        </table>
        <table border="1">
            <tr>
                <th>s.n0</th>
                <th>course code</th>
                <th>course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI302</td>
                <td>Engineering Design and Modelling(edm)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301</td>
                <td>python Programming(python)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application(web)</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19EN101</td>
                <td>Communicative English(eng)</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EY708</td>
                <td>Career Development Skills(cds)</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra(mat)</td>
             </tr>
                <tr>
                    <td>7.</td>
                    <td>ECA-M-SCOFT</td>
                    <td>Mentor Meet(mentor)</td>
                </tr>
                <tr>
                    <td>8.</td>
                    <td>SH3214</td>
                    <td>Physics for Quantum Computing(phy)</td>
                </tr>
                
                </center>
        </table>
    </body>
</html>
```
## OUTPUT
![alt text](image-1.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
