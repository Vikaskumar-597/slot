# Ex03 Time Table
## Date: 18/11/2024

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
    <body>
        <center>
            <img src="/static/logo.png" height="150" width="800">
        </center>
        <table border="3" cellpadding="7" align="center" bgcolor="cyan">
            <caption ><b><h2>SLOT TIMETABLE - VIKASKUMAR M (24900247)</h2></b></caption>
            <tr>
                <th bgcolor="yellow">DAY/TIME</th>
                <th bgcolor="yellow">MONDAY</th>
                <th bgcolor="yellow">TUESDAY</th>
                <th bgcolor="yellow">WEDNESDAY</th>
                <th bgcolor="yellow">THURSDAY</th>
                <th bgcolor="yellow">FRIDAY</th>
                <th bgcolor="yellow">SATURDAY</th>
            </tr>
            <tr>
                <th bgcolor="yellow">8-10</th>
                <td>FREESLOT</td>
                <td>BEEME</td>
                <td >CRYPTO</td>
                <td>FREESLOT</td>
                <td>EMPD</td>
                <td>FREESLOT</td>
            </tr>
            <tr>
                <th bgcolor="yellow">10-12</th>
                <td >CRYPTO</td>
                <td>DE</td>
                <td>BEEME</td>
                <td>C PROGRAM</td>
                <td>DE</td>
                <td>FWAD</td>
            </tr>
             <tr>
                <th bgcolor="yellow">12-1</th>
                <td colspan="6" align="center" >LUNCH BREAK</td>
            </tr>
            <tr>
                <th bgcolor="yellow">1-3</th>
                <td>CDS</td>
                <td>FWAD</td>
                <td>M-M</td>
                <td>FWAD</td>
                <td>C PROGRAM</td>
                <td>EMPD</td>
            </tr>
            <tr>
                <th bgcolor="yellow">3-5</th>
                <td colspan="6" align="center" >FREESLOT</td>
            </tr>
           
        </table><br><br>
        <table border="2" cellpadding="7" align="center">
            <tr>
                <th>S.NO.</th><th>SUBJECT CODE</th><th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td align="center">19AI303</td>
                <td>Engineering Mechanics and Product Development(EMPD)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of C Programming(C-PROGRAM)</td>
            </tr>
            <tr>
                <td>4.</td>
                <td align="center">19EE305</td>
                <td>Basic Electrical, Electronics And Measurement Engineering(BEEME)</td>
            </tr>
            <tr>
                <td>5.</td>
                <td align="center">19EE404</td>
                <td>Digital Electronics(DE)</td>
            </tr>
            <tr>
                <td>6.</td>
                <td align="center">19CS547</td>
                <td>Fundamentals Of Cryptocurrency(CRYPTO)</td>
            </tr>
            <tr>
                <td>7.</td>
                <td align="center">19EY708</td>
                <td>Career Development Skills(CDS)</td>
            </tr>
            <tr>
                <td>8.</td>
                <td align="center">TSIT023</td>
                <td>Mentor Meet(M-M)</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot 2024-11-18 215306.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
