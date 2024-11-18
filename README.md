# Ex03 Time Table
## Date:18-11-2024

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
    <head>
    </head>
    <body>
        <center>
        <img src="logo.png" width="780" height="100">
        </center>
        <br>
        <table align="center" BORDER="4" width="750" bgcolor="white" cellspacing="5" cellpadding="5">
        <caption><h1 align="center" > Aadipranav's Slot Table[24007963]</h1></caption>
            <TR align="center" bgcolor="cyan"> 
                <TH>DAY/TIME</TH><TH>MONDAY</TH><TH>TUESDAY</TH><TH>WEDNESDAY</TH><TH>THURSDAY</TH><TH>FRIDAY</TH><TH>SATURDAY</TH>
            </TR>  
            <TR> <TH bgcolor="cyan">CLASS1  [8-10]</TH>
                <TH bgcolor="white">-</TH>
                <TH bgcolor="orange">COMMUNICATIVE ENGLISH</TH>
                <TH bgcolor="lightgreen">STATISTICS</TH>
                <TH bgcolor="white">-</TH>
                <TH bgcolor="orange">COMMUNICATIVE ENGLISH</TH>
                <TH bgcolor="white">-</TH>
            </TR> 
            <TR>
                <TH bgcolor="cyan">CLASS2  [10-12</TH>
                <TH bgcolor="purple">WEBAPP</TH>
                <TH bgcolor="pink">DIG ELEC</TH>
                <TH bgcolor="purple">WEBAPP</TH>
                <TH bgcolor="pink">DIG ELEC</TH>
                <TH bgcolor="red">PHYSICS</TH>
                <TH bgcolor="gray">C PROGRAMING</TH>
            </TR>
            <TR>
                <TH bgcolor="cyan">CLASS3  [1-3]</TH><TH>-</TH>
                <TH bgcolor="lightgreen">STATISTICS</TH>
                <TH bgcolor="yellow">MENTOR MEET</TH>
                <TH bgcolor="red">PHYSICS</TH>
                <TH bgcolor="gray">C PROGRAMING</TH>
                <TH bgcolor="purple">WEBAPP</TH>
            </TR>
            <table align="center" width="540" cellspacing="2" cellpadding="4" border="5"</table>
                <br>
                <tr align="center"   >
                        <th >S.NO</th>
                        <th>Subject Code</th>
                        <th >Subject Name</th>
                  </tr>
                <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of web application</td>
                </tr>
                <tr>
                <td>2</td>
                <td>19EE404</td>
                <td>Digital electronics</td>
                </tr>
                <tr>
                <td>3</td>
                <td>19MA211</td>
                <td>Statistics and numerical methods</td>
                </tr>
                <tr>
                <td>4</td>
                <td>19AI304</td>
                <td>Fundamentals of C programing</td>
                </tr>
                <tr>
                <td>5</td>
                <td>19EN101</td>
                <td>Communicative english</td>
                </tr>
                <tr>
                <td>6</td>
                <td>SH3214</td>
                <td>Physics for quantum computing</td>
                </tr>
                <tr>
                    <td>7</td>
                    <td>ECAM SCOFT</td>
                    <td>Mentor meet</td>
                </tr>
        </table>
        </body>
        </html>

## OUTPUT

![Screenshot 2024-11-18 110228](https://github.com/user-attachments/assets/f3b412df-7689-4e15-8924-c518a1e26e41)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
