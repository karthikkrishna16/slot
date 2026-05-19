# Ex02 Time Table
## Date: 12/05/2026

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
<title>Slot Time Table</title>
</head>

<body bgcolor="lightyellow">
    <center>
        <img src="/static/logo.png" height = 100 width="540">

    </center>

<table border="2" cellpadding="10" align="center" width="90%" bgcolor="black">

<caption>
<b>SLOT TIME TABLE - karthik krishna (212223240067) </b>
</caption>

<tr bgcolor="yellow">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>

<tr bgcolor="cyan">
<td>8-10</td>
<td colspan="2" align="center">FREE SLOT</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>FREE SLOT</td>
</tr>


<tr bgcolor="cyan">
<td>10-12</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>WEB MINING</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>WEB MINING</td>
</tr>


<tr bgcolor="cyan">
<td>12-1</td>
<td colspan="6" align="center">L U N C H</td>
</tr>

<tr bgcolor="cyan">
<td>1-3</td>
<td>DBMS</td>
<td>FWAD</td>
<td>MENTOR MEET</td>
<td>WEB MINING</td>
<td>WEB MINING</td>
<td rowspan="2" align="center">FREE SLOT</td>
</tr>


<tr bgcolor="cyan">
<td>3-5</td>
<td>WEB MINING</td>
<td>FREE SLOT</td>
<td>DBMS</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>


</table>

<br><br>

<table border="2" cellpadding="8" align="center" width="80%" bgcolor="black">

<caption>
<b>SUBJECT DETAILS</b>
</caption>

<tr bgcolor="white">
<th>S.No</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr bgcolor="white">
<td>1</td>
<td>19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION(FWAD)</td>
</tr>

<tr bgcolor="white">
<td>2</td>
<td>19AI412</td>
<td>WEB DATA MINING</td>
</tr>

<tr bgcolor="white">
<td>3</td>
<td>19CS404</td>
<td>DATABASE MANAGEMENT SYSTEM AND ITS APPLICATION</td>
</tr>

</table>


</body>
</html>
```

## OUTPUT
<img width="1048" height="547" alt="{C1E1438E-F7A0-47B2-BA91-629620F9A118}" src="https://github.com/user-attachments/assets/0efcd8c0-ec6b-4513-b09b-b7f10f743eba" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
