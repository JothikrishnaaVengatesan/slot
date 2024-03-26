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
        <table  align="center" bgcolor="black" width="540" cellspacing="2" cellpadding="4" border="2">
            <caption><b>SLOT TIMETABLE -- JOTHIKRISHNAA V (212223100017)</b></caption>
            <tr align="center">
                <th bgcolor="red">Day/Time</th>
                <th bgcolor="red">Monday</th>
                <th bgcolor="red">Tuesday</th>
                <th bgcolor="red">Wednesday</th>
                <th bgcolor="red">Thursday</th>
                <th bgcolor="red">Friday</th>
            <tr bgcolor="navy" align="center">
                <th bgcolor="blue">8-10</th>
                <td bgcolor="fuchsia"> C </td>
                <td bgcolor="yellow"> ENG </td>
                <td bgcolor="green"> PHY </td>
                <td bgcolor="gray"> MAT </td>
                <td bgcolor="fuchsia"> C </td>
            </tr>
            <tr bgcolor="navy" align="center">
                <th bgcolor="blue">10-12</th>
                <td bgcolor="cyan"> FREE SLOT </td>
                <td bgcolor="pink"> FWAD </td>
                <td bgcolor="purple"> CHE</td>
                <td bgcolor="cyan"> FREE SLOT </td>
                <td bgcolor="gray"> MAT </td>
            </tr>
            <tr bgcolor="navy" align="center">
                <th bgcolor="gold">12-1</th>
                <td bgcolor="gold" colspan="5" align="center"> L U N C H </td>
            </tr>
            <tr bgcolor="navy" align="center">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="cyan"> FREE SLOT </td>
                <td bgcolor="cyan"> FREE SLOT </td>
                <td bgcolor="pink"> FWAD </td>
                <td bgcolor="green"> PHY </td>
                <td bgcolor="purple"> CHE</td>
            </tr>
            <tr bgcolor="navy" align="center">
                <th bgcolor="blue">3-5</th>
                <td bgcolor="gray"> MAT </td>
                <td bgcolor="lime"> SS </td>
                <td bgcolor="pink"> FWAD </td>
                <td bgcolor="green"> PHY </td>
                <td bgcolor="purple"> CHE</td>
            </tr>

        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th bgcolor="cyan">S.No.</th>
                <th bgcolor="teal">Subject Code</th>
                <th bgcolor="teal">Subject Name</th>
            </tr> 
            <tr>
                <td bgcolor="cyan" align="center">1.</td>
                <td bgcolor="pink"align="center">19AI414</td>
                <td bgcolor="pink">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT (FWAD)</td>
            </tr>
            <tr>
                <td bgcolor="cyan" align="center">2.</td>
                <td bgcolor="fuchsia"align="center">19AI304</td>
                <td bgcolor="fuchsia">FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
            </tr>
            <tr>
                <td bgcolor="cyan" align="center">3.</td>
                <td bgcolor="green"align="center">19PH214</td>
                <td bgcolor="green">PHYSICS FOR QUANTUM COMPUTATION (PHY)</td>
            </tr>
            <tr>
                <td bgcolor="cyan" align="center">4.</td>
                <td bgcolor="purple" align="center">19CY205</td>
                <td bgcolor="purple">PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</td>
            </tr>
            <tr>
                <td bgcolor="cyan" align="center">5.</td>
                <td bgcolor="gray" align="center">19MA211</td>
                <td bgcolor="gray">STATISTICS AND NUMERICAL METHODS (MAT)</td>
            </tr>
            <tr>
                <td bgcolor="cyan" align="center">6.</td>
                <td bgcolor="lime" align="center">19EY701</td>
                <td bgcolor="lime">SOFT SKILLS (SS)</td>
            </tr>
            
        </table>
    </body>
</html>
~~~
## OUTPUT
![alt text](<Screenshot 2024-03-26 111953.png>)
![alt text](<Screenshot 2024-03-20 231614.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
