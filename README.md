# Ex03 Time Table
## Date:
20/03/2024
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
~~~
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100"width="540">
        </center>
        <br>
        <table align="center" bgcolor="cyan" width="540" cellspacing="2" cellpadding="4" border="2">
            <caption><b>SLOT TIMETABLE JOTHIKRISHNAA V (212223100017)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="yellow">8-10</th>
                <td > C </td>
                <td > ENG </td>
                <td > PHY </td>
                <td > MAT </td>
                <td > C </td>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="yellow">10-12</th>
                <td > FREE SLOT </td>
                <td > FWAD </td>
                <td > CHE</td>
                <td > FREE SLOT </td>
                <td > MAT </td>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="yellow">12-1</th>
                <td colspan="5" align="center"> L U N C H </td>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="yellow">1-3</th>
                <td >FREE SLOT</td>
                <td >FREE SLOT</td>
                <td >FWAD</td>
                <td >PHY</td>
                <td >CHE</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td > MAT </td>
                <td > SS </td>
                <td > FWAD </td>
                <td > PHY </td>
                <td > CHE </td>
            </tr>

        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19PH214</td>
                <td>PHYSICS FOR QUANTUM COMPUTATION (PHY)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19MA211</td>
                <td>STATISTICS AND NUMERICAL METHODS (MAT)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
            
        </table>
    </body>
</html>
~~~
## OUTPUT
![1](<Screenshot 2024-03-22 092102.png>)
![alt text](<Screenshot 2024-03-20 231614.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
