# Ex03 Time Table
# Date:28-03-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
<title>SLOT TIME TABLE</title> 
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="900">
</center>
<br>
<table align="center" width="540" border="5" bgcolor="lightblue" cellspacing="5" cellpadding="10">
<caption><b>SLOT TIME TABLE NAVINKUMAR.S(212224110041)</b></caption>
            
<tr align="center">
<th bgcolor="darkgrey">Timings/Days</th>
<th bgcolor="darkgrey">Monday</th>
<th bgcolor="darkgrey">Tuesday</th>
<th bgcolor="darkgrey">Wednesday</th>
<th bgcolor="darkgrey">Thursday</th>
<th bgcolor="darkgrey">Friday</th>
<th bgcolor="darkgrey">Saturday</th>
</tr>
<tr align="center"> 
<td bgcolor="darkgrey"><b>8-10</b></td>
<td>Free slot</td>
<td>Free slot</td>
<td>Free slot</t>
<td>Free slot</td>
<td>Free slot</td>
<td>Free slot</td>
</tr>
<tr align="center"> 
<td bgcolor="darkgrey"><b>10-12</b></td>
<td>BEEME</td>
<td>EMPD</td>
<td>PQC</td>
<td>Free slot</td>
<td>PQC</td>
<td>Free slot</td>
</tr>
<tr align="center"> 
<td bgcolor="darkgrey"><b>12-1</b></td>
<th colspan="6">Lunch Break</th>
                
</tr>
<tr align="center">
<td bgcolor="darkgrey"><b>1-3</b></td>
<td>Free slot</td>
<td>FWAD</td>
<td>Mentor Meet</td>
<td>PQM</td>
<td>FWAD</td>
<td>PCE</td>
</tr>
<tr align="center"> 
<td bgcolor="darkgrey"><b>3-5</b></td>
<td>PCE</td>
<td>Free slot</td>
<td>Free slot</td>
<td>EMPD</td>
<td>BEEME</td>
<td>PQM</td>
</tr>
</table>
<br>
<center>
<table border="2" cellspacing="10" cellpadding="10" bgcolor="lightblue">
</center>    
<tr>
<td bgcolor="darkgrey"><b>S.NO</b></td>
<td bgcolor="darkgrey"><b>Subject Code</b></td>
<td bgcolor="darkgrey"><b>Subject Name</b></td>
</tr>
<tr>
<td align="center" bgcolor="darkgrey"><b>1.</b></td>
<td align="center" bgcolor="lightblue">19AI414</td>
<td bgcolor="lightblue">Fundementals of Web Application Development (FWAD)</td>

</tr>
<tr>
<td align="center" bgcolor="darkgrey"><b>2.</b></td>
<td align="center" bgcolor="lightblue">19AI303</td>
<td bgcolor="lightblue">Engineering Mechanics and Product Development (EMPD)</td>
</tr>
<tr>
<td align="center" bgcolor="darkgrey"><b>3.</b></td>
<td align="center" bgcolor="lightblue">19CY205</td>
<td bgcolor="lightblue">Principles of Chemistry in Engineering (PCE)</td>
</tr>
<tr>
<td align="center" bgcolor="darkgrey"><b>4.</b></td>
<td align="center" bgcolor="lightblue">19EE305</td>
<td bgcolor="lightblue">Basic Electrical,Electronics and Measurement Engineering (BEEME)</td>
</tr>
<tr>
<td align="center" bgcolor="darkgrey"><b>5.</b></td>
<td align="center" bgcolor="lightblue">19MA222</td>
<td bgcolor="lightblue">Probability and Queueing Models (PQM)</td>
</tr>
<tr> 
<td align="center" bgcolor="darkgrey"><b>6.</b></td>
<td align="center" bgcolor="lightblue">19PH814</td>
<td bgcolor="lightblue">Physics for Quantum Computing (PQC)</td>
</tr>
<tr> 
<td align="center" bgcolor="darkgrey"><b>7.</b></td>
<td align="center" bgcolor="lightblue">ECA-M-SCOFT</td>
<td bgcolor="lightblue">Mentor Meet</td>
</tr>
</table>
</body>
</html>
```
# OUTPUT
![Screenshot 2025-03-28 175810](https://github.com/user-attachments/assets/96a70d9b-6885-4dd5-87ba-626bcee69398)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
