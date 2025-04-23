# Ex03 Time Table
## Date:

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
<html>
    <body>
        <img src="logo.png">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>SLOT TIME TABLE YOGESWARI (24011145)</caption>
            <tr bgcolor="cyan" align="center">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center">
                <td>8-10</td>
                <td colspan="4">FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
            <TR bgcolor="pink" align="center">
                <td>10-12</td>
                <td>PHY</td>
                <td>FREE SLOT</td>
                <td colspan="3">FCP</td>
                <td>CDS</td>
            </TR>
            <tr align="center">
                <td>12-1</td>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr bgcolor="pink" align="center"> 
                <td>1-3</td>
                <td colspan="2">FWAD</td>
                <td>MM</td>
                <td>PHY</td>
                <td>FREE SLOT</td>
                <td>BEEE</td>
            </tr>
            <tr align="center">
                <td>3-5</td>
                <td colspan="2">FREE SLOT</td>
                <td colspan="2">PCE</td>
                <td colspan="2">FREE SLOT</td>

            </tr>
        </table>
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>Subject and Subject Code</caption>
            <tr>
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EE305</td>
                <td>Basic Electrical,Electronics and Measurement Engineering</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>SH3214</td>
                <td>Physics of Quantum Computing</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
        </table>
    </body>
</html>


## OUTPUT
![Screenshot 2025-04-23 193318](https://github.com/user-attachments/assets/904b56be-20c7-4c83-ae50-361bcfa6e0e6)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
