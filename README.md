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
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE JOTHIKRISHNAA V (212223100017)</b></caption>
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
                <td bgcolor="blue">FUNDAMENTALS OF C PROGRAMMING</td>
                <td bgcolor="blue">COMMUNICATIVE ENGLISH</td>
                <td bgcolor="blue">PHYSICS FOR QUANTUM COMPUTATION</td>
                <td bgcolor="blue">STATISTICS AND NUMERICAL METHODS</td>
                <td bgcolor="blue">FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">10-12</th>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="blue">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">STATISTICS AND NUMERICAL METHODS</td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">12-1</th>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="blue">PHYSICS FOR QUANTUM COMPUTATION</td>
                <td bgcolor="blue">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">12-1</th>
                <td bgcolor="blue">STATISTICS AND NUMERICAL METHODS</td>
                <td bgcolor="blue">SOFT SKILLS</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="blue">PHYSICS FOR QUANTUM COMPUTATION</td>
                <td bgcolor="blue">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
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
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT (FWAD)</td>
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
![alt text](<Screenshot 2024-03-20 231535.png>)
![alt text](<Screenshot 2024-03-20 231614.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
