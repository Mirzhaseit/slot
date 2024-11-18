# Ex03 Time Table
## Date:17-11-2024

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
'''
<html>
<body>
<img src="logo.png" width="700" height="200" alt="Logo Image">
<table border="2" cellspacing="15" cellpadding="5">
     <caption>SLOT TIMETABLE-MIRZHA FATHIMA.S(24901261)</caption>
     <tr bgcolor="yellow">
        <th>DAY/TIME</th>
        <th> MONDAY</th>
        <th> TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
   </tr>
   <tr>
   <td>8-10</td>
   <td>FREE SLOT</td>
   <td>WEB</td>
   <td>PYTHON</td>
   <td colspan="3">FREE SLOT</td>
</tr>
<tr>
   <td>10-12</td>
   <td>PYTHON</td>
   <td>GERMAN</td>
   <td>CAREER</td>
   <td>ENGLISH</td>
   <td>WEB</td>
   <td>GERMAN</td>
</tr>
<tr>
   <td>12-1</td>
   <td colspan="6">LUNCH BREAK</td>
</tr>
<tr>
<td>1-3</td>
<td>EDM</td>
<td>ENG</td>
<td>MENTOR</td>
<td>EDM</td>
<td>FREESLOT</td>
<td>WEB</td>
</tr>
<tr>
    <td>3-5</td>
    <td colspan="6">FREE SLOT</td>
</tr>
</table>
<table border="2" cellspacing="15" cellpadding="5">
    <caption>COURSES</caption>
        <tr bgcolor="cyan">
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
         </tr>
         <tr>
             <td>1</td>
             <td>19AI414</td>
             <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT(WEB)</td>
         </tr>
         <tr>
             <td>2</td>
             <td>19AI301</td>
             <td>PYTHON PROGRAMMING</td>
         </tr>
         <tr>
             <td>3</td>
             <td>6H-1</td>
             <td>GERMAN</td>
         </tr>
         <tr>
             <td>4</td>
             <td>19EN101</td>
             <td>ENGLISH(ENG)</td>
        </tr>
        <tr>
             <td>5</td>
             <td>19AI302</td>
             <td>EDM</td>
        </tr>
        <tr>
             <td>6</td>
             <td>19EY708</td>
             <td>CAREER DEVELOPEMENT SKILLS</td>
         </tr>
         <tr>
             <td>7</td>
             <td>ECA-M-SCOFT</td>
             <td>MENTOR MEET</td>
          </tr>
</table>
</body>
</html>
'''
### OUTPUT
![alt text](<Screenshot (59).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
