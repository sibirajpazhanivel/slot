# Ex03 Time Table

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

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - SIBIRAJ P(22009463)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>C PROGRAM</td>
<td>ENG</td>
<td>PHY</td>
<td>MAT</td>
<td>C PROGRAM</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td> FWAD </td>
<td>FREE SLOT</td>
<td>CHE</td>
<td>MAT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td> FREE SLOT </td>
<td>FREE SLOT</td>
<td>ENG</td>
<td>FWAD</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td> MAT </td>
<td>CHE</td>
<td>FWAD</td>
<td>PHY</td>
<td>SS</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EN101</td>
<td>Communicative english(ENG)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH214</td>
<td>Physics for quantum computing (PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statistics and numerical methods (MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>Soft Skills (SS)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C programming (C PROGRAM)</td>
</tr>
</table>
</body>
</html>

```


## OUTPUT:
![OUTPUT](https://github.com/sibirajpazhanivel/slot/assets/121081515/fe24c799-a368-4c69-82e2-4d0ef061c8ab)




## HTML VALIDATOR:
![HTML VALIDATOR](https://github.com/sibirajpazhanivel/slot/assets/121081515/591d5fe4-473d-4359-ae69-c9530bb94afe)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
