# Ex03 Time Table
## Date:25.11.2024

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
```
DOCTYPE! html>
<html>
    <head>
        <title>My Timetable</title>
    </head>
    <body text="black">
        <img src="/static/logo.png" width="610">
        <br><br>
        <table border="3" cellpadding="10" bgcolor="aqua" width="546">
            <caption><B>SLOT TIMETABLE - JONES BENEDICT A P (24900206)</B></caption>
            <tr bgcolor="white">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Satuday</th>
            </tr>
            <tr>
                <th bgcolor="white">8-10</th>
                <th></th>
                <th></th>
                <th>M-1</th>
                <th>ENG</th>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <th bgcolor="white">10-12</th>
                <th>ENG</th>
                <th>EDM</th>
                <th>C</th>
                <th>M-1</th>
                <th>C</th>
                <th>FWAD</th>
            </tr>
            <tr>
                <th bgcolor="white">12-1</th>
                <th colspan="6">LUNCH</th>
            </tr>
            <tr>
                <th bgcolor="white">1-3</th>
                <th></th>
                <th>FWAD</th>
                <th>MENTOR</th>
                <th>FWAD</th>
                <th>EDM</th>
                <th></th>
            </tr>
            <tr>
                <th bgcolor="white">3-5</th>
                <th></th>
                <th></th>
                <th></th>
                <th></th>
                <Th>CARE-DEV</Th>
                <Th></Th>
            </tr>
            </font>
        </table>
        <br>
        <table border="4" cellspacing="5" width="615">
            <tr>
                <th>S.NO.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1.</th>
                <th>19A1302</th>
                <th>ENGINEERING DESIGN AND MODELLING</th>
            </tr>
            <tr>
                <th>2.</th>
                <th>19AI304</th>
                <th>FUNDAMENTALS OF C PROGRAMMING</th>
            </tr>
            <tr>
                <th>3.</th>
                <th>19A1414</th>
                <th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</th>
            </tr>
            <tr>
                <th>4.</th>
                <th>19EN101</th>
                <th>COMMUNICATED ENGLISH</th>
            </tr>
            <tr>
                <th>5.</th>
                <th>19MA201</th>
                <th>CALCULUS AND MATRIX ALGEBRA</th>
            </tr>
            <tr>
                <th>6.</th>
                <th>ECA-M</th>
                <th>MENTOR MEET</th>
            </tr>
            <tr>
                <th>7.</th>
                <th>19EY708</th>
                <th>CAREER DEVELOPMENT SKILLS</th>
            </tr>
        </table>
        <BR><BR>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-25 214911.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
