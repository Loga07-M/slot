# Ex02 Time Table
## Date:26/11/2025

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
```
<html>
    <head>
        <title>slot</title>
    </head>
    <body>
        <div style="text-align:center;">
        <img width="800" height="188" src="logo.png" >
        </div>
        <div style="margin-top: 30px;"></div>
        <table bgcolor="#A4F0F2" border="5" width="800" height="200" align="center" border="1">
            <caption><b>SLOT TIME TABLE-LOGA SRI M (25012855) </b></caption>
            <tr bgcolor="Yellow">
                <th>DAY/TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th> 
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <td bgcolor="Yellow" align="center"><b>8-10</b></td>
                <td align="center">FREE SLOT</td>
                <td align="center">C</td>
                <td colspan="2" align="center">FREE SLOT</td>
                <td align="center">FWAD</td>
                <td align="center">FREE SLOT</td>

            </tr>
            <tr>
                <td bgcolor="Yellow" align="center">10-12</td>
                <td align="center">C</td>
                <td align="center">COM ENG</td>
                <td align="center">FREE SLOT</td>
                <td align="center">COM ENG</td>
                <td colspan="2" align="center">FWAD</td>
            </tr>
            <tr>
                <td bgcolor="Yellow" align="center">12-1</td>
                <td colspan="5" align="center">LUNCH</td>
            </tr>
            <tr>
                <td bgcolor="Yellow" align="center">1-3</td>
                <td colspan="2" align="center">FWAD</td>
                <td>MENTOR MEET</td>
                <td>COM ENG</td>
                <td colspan="2" align="center">FREE SLOT</td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">3-5</td>
                <td align="center">FREE SLOT</td>
                <td colespan="3" align="center">C</td>
                <td align="center">FREE SLOT</td>
                <td align="center">ENG</td>
            </tr>
        </table>
        <div style="margin-top: 40px;"></div>
        <table width="800" height="195" align="center" border="1">
            <tr>
                <th align="center">S.NO.</th>
                <th align="center">Subject Code</th>
                <th align="center">Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EN101</td>
                <td >Communicative English (COM ENG)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of C Programming (C) </td>
            </tr>
            </table>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (18).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
