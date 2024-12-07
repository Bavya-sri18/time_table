# Ex03 Time Table
# Date: 21.10.2024
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Time Table</title>
    <style>
        body{
            font-family:sans-serif;
        }
        
         table {
            border-collapse: collapse;
            margin: 20px auto;
            width: 80%;
        }
        .main{
            text-align: center;
            margin: 20px;

        }
        th, td {
            border: 3px solid #000;
            padding: 10px;
            text-align: center;
        }
        th{
            background-color:coral;
        }
        td{
            background-color:rgb(98, 245, 242);
        }

    </style>
</head>
<body>
    <div class="main">
        <img src="/static/saveetha1.png" alt="Saveetha Engineering College" width="1000"height=100>
        <h1>SLOT TIMETABLE - BAVYA SRI B(24900078)</h1>
    </div>
    <TABLE>
        <tr>
            <th>DAY/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>
        <tr>
            <td style="background-color: coral;">8-10</td>
            <td>DE</td>
            <td colspan="3">FREE SLOT</td>
            <td>PHY</td>
            <td>ENG</td>
        </tr>
        <tr>
            <td style="background-color: coral;">10-12</td>
            <td>CDS</td>
            <td>PHY</td>
            <td>ENG</td>
            <td>MATH</td>
            <td colspan="2">FWAD</td>
        </tr>
        <tr>
            <td style="background-color: coral;">12-1</td>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr>
            <td style="background-color: coral;">1-3</td>
            <td>FWAD</td>
            <td>DE</td>
            <td>MM</td>
            <td colspan="2">FCP</td>
            <td>MATH</td>
        </tr>
    </TABLE>
<table>
    <tr>
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td> 19AI414 </td>
        <td>Fundamentals of web application development(FWAD)</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19EN101</td>
        <td>Communicative English(CE)</td>
    </tr>
    <TR>
        <TD> 3</TD>
        <td>SH3214</td>
        <td>Physics for quantum computing(PHY)</td>
    </TR>
    <TR>
        <td>4</td>
        <td>19EY708</td>
        <td>Career development skills(CDS)</td>
    </TR>
    <tr>
        <td>5</td>
        <td>19EE404</td>
        <td>Digital Electronics(DE)</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19AI304</td>
        <td>Fundamentals of C programming(FCP)</td>
    </tr>
    <tr>
        <td>7</td>
        <td>19MA222</td>
        <td>Probability and queueing models(MATH)</td>
    </tr>
</table>

        
</body>
</html>
```
# OUTPUT

![SLOT TIMETABLE](https://github.com/user-attachments/assets/51a25ab4-396a-44ca-847f-cd1eec891778)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
