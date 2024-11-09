# Ex04 Time Table
## Date:06-11-2024

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
<html>
    <head></head>
	<body align="center" bgcolor="white">
		 <center>
            <img src="/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="BLUE">
			<caption>SLOT TIME TABLE - ANBUSELVAN S (212223110003)</caption>
            <br>
			<tr>
				<th bgcolor="RED"> Day/Time </th>
				<th bgcolor="RED"> Monday </th>
				<th bgcolor="RED"> Tuesday </th>
                <th bgcolor="RED"> Wednesday </th>
                <th bgcolor="RED"> Thursday </th>
                <th bgcolor="RED"> Friday </th>
                <th bgcolor="RED"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="RED"> 8-10 </th>
                <td> ENGLISH </td>
                <td> TAMIL </td>
                <td> MATHS </td>
                <td> PHYSICS </td>
                <td> CHEMISTRY </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="RED"> 10-12 </th>
				<td> DATA SCIENCE </td>
                <td> PROFESSIONAL ETHICS </td>
                <td> WEB </td>
                <td> FREE SLOT </td>
                <td> CHEMISTRY </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="RED"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="RED"> 1-3 </th>
                <td> INTRO TO ML </td>
                <td> FREE SLOT </td>
                <td> MATHS </td>
                <td> PROFESSIONAL ETHICS </td>
                <td> DATA SCIENCE </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="RED"> 3-5 </th>
                <td> CHEMISTRY </td>
                <td> PHYSICS </td>
                <td> MATHS </td>
                <td> DATA SCIENCE </td>
                <td> INTRO TO ML </td>
                <td> WEB </td>
			</tr>
		</table>
        <br>
        <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="BLUE">
            <br>
            <tr>
                <th align="center"> S.No </th>
                <th align="center"> Subject Code </th>
                <th align="center"> Subject Name </th>
            </tr>
            <tr>
                <th> 1. </th>
                <td align="center"> 21EN101 </td>
                <td align="center"> ENGLISH </td>
            </tr>
            <tr>
                <th> 2. </th>
                <td align="center"> 21TA102 </td>
                <td align="center"> TAMIL </td>
            </tr>
            <tr>
                <th> 3. </th>
                <td align="center"> 21MA103 </td>
                <td align="center"> MATHS </td>
            </tr>
            <tr>
                <th> 4. </th>
                <td align="center"> 21PH104 </td>
                <td align="center"> PHYSICS </td>
            </tr>
            <tr>
                <th> 5. </th>
                <td align="center"> 21CH105 </td>
                <td align="center"> CHEMISTRY </td>
            </tr>
            <tr>
                <th> 6. </th>
                <td align="center"> 21DS106 </td>
                <td align="center"> DATA SCIENCE </td>
            </tr>
            <tr>
                <th> 7. </th>
                <td align="center"> 21PE107 </td>
                <td align="center"> PROFESSIONAL ETHICS </td>
            </tr>
            <tr>
                <th> 8. </th>
                <td align="center"> 21ML108 </td>
                <td align="center"> INTRODUCTION TO MACHINE LEARNING (INTRO TO ML) </td>
            </tr>
            <tr>
                <th> 9. </th>
                <td align="center"> 21WA109 </td>
                <td align="center"> WEB APPLICATIONS (WEB) </td>
            </tr>
            <tr>
                <th> 10. </th>
                <td align="center"> N/A </td>
                <td align="center"> FREE SLOT </td>
            </tr>
        </table>
	</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (61).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
