# Ex04 Time Table
## Date : 21-11-2026

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
Table.html 

<html>
<head>
    <link rel="stylesheet" href="Stylesheet.css">
    <title>TIME TABLE</title>
</head>
<body>
    <center>
        <img class="lo" src="sec.png" alt="Saveetha logo">
        <h1 class="name">TIME TABLE - AAKASH M (26001770)</h1>
        <table  border="2">
            <tr class="first">
                <th>DAY / TIME</th>
                <th>08:00 - 09:29</th>
                <th>09:45 - 11:14</th>
                <th>12:00 - 12:59</th>
                <th>01:15 - 02:44</th>
                <th>03:00 - 04:29</th>
            </tr>
            <tr>
                <th>MONDAY</th>
                <td  colspan="2" align="center" > FREE</td>
                <td>MENTOR MEET</td>
                <td>FREE</td>
                <td>DE</td>
            </tr>
            <tr>
                <th>TUESDAY</th>
                <td>FREE</td>
                <td>CALCULUS</td>
                <td>MENTOR MEET</td>
                <td>CALCULUS</td>
                <td>PYTHON</td>
            </tr>
            <tr>
                <th>WEDNESDAY</th>
                <td colspan="2" align="center">FREE</td>
                <td>MENTOR MEET</td>
                <td>FREE</td>
                <td>B.EEE</td>
            </tr>
            <tr>
                <th>THURSDAY</th>
                <td>ENGLISH</td>
                <td>PYTHON</td>
                <td>MENTOR MEET</td>
                <td>FREE</td>
                <td>DE</td>
            </tr>
             <tr>
                <th>FRIDAY</th>
                <td>ENGLISH</td>
                <td>FREE</td>
                <td>MENTOR MEET</td>
                <td>FWAD</td>
                <td>EDM</td>
            </tr>
               <tr>
                <th>SATURDAY</th>
                <td>PYTHON</td>
                <td>FWAD</td>
                <td>MENTOR MEET</td>
                <td>FWAD</td>
                <td>EDM</td>
            </tr>
        </table>
        <br>
        <br>
        <table border="3" class="sub">
        <tr class="Sec">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr >
                <th>1</th>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <th>2</th>
                <td>19AI302</td>
                <td>Engineering Design and Modelling (EDM)</td>
            </tr>
            <tr>
                <th>3</th>
                <td>19AI301</td>
                <td>Python Programming (PYTHON)</td>
            </tr>
            <tr>
                <th>4</th>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra (CALCULUS)</td>
            </tr>
            <tr>
                <th>5</th>
                <td>SH1101-19EN101</td>
                <td>Communicative English (ENGLISH)</td>
            </tr>
            <tr>
                <th>6</th>
                <td>19EE305</td>
                <td>Basic Electrical, Electronics and Measurement Engineering (B.EEE)</td>
            </tr>
            <tr>
                <th>7</th>
                <td>19EE404</td>
                <td>Digital Electronics (D.E)</td>
            </tr>
        </table>
    </center>
</body>
</html>

Stylesheet.css

.first{
    background-color: #0ad9ec;
}
table{
    border-color: #117fa4;
}
.lo{
    width: 600px; 
    height: 150px;
}
th{
    padding: 10px;
}
.Sec{
    background-color: #0ad9ecc0;
}
td{
    padding: 12px;
}
.name{
    color: #003b89;
    font-size: 20px;
}


```

## OUTPUT

![alt text](<Screenshot (28).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
