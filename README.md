# Ex03 Time Table
## Date:08-10-2025

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
    <center><IMG SRC="slot/logo.png"align="center" HEIGHT="110"WIDTH="900"></body>
    <h2 align="center">Slot Timetable - VENKATESH.P(25011427)</h2>
    
    

    <table border="1" align="center" height="10" width="40" celspadding="8" celspacing="8"  margin-bottom: 20px>
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">8-10</th>
            <td>C programming</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">10-12</th>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>FREE SLOT</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">12-1</th>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">1-3</th>
            <td>C Programming</td>
            <td>DATA SCIENCE</td>
            <td>Mentor meet</td>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">3-5</th>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>c Programming</td>
            <td>DATA SCIENCE</td>
            <td>FREE SLOT</td>
            <td>c programming</td>
        </tr>
    </table>


    <h3>Subjects</h3>

    <table border="2" align="center" height="100" width="590" celspacing="8" celspading="8" margin-bottom="20">
       
       
        <tr>

            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>

        </tr>
        <tr>
            <th>1.</th>
            <th>19AI414</th>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <th>2.</th>
            <th>19AI304</th>
            <td>c Programing (cP)</td>
        </tr>
         <tr>
            <th>3.</th>
            <th>19A1403</th>
            <td>Introduction of data science</td>
        </tr>
        
    </table>
</body>
</html>

## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/876f9119-c42c-4ab5-8dff-fe522afd4aa6" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
