# Ex03 Time Table
# Date:26.11.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table.> tag in html.

## STEP 4
Add header row using <th.> tag.

## STEP 5
Add your timetable using <td.> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        h1 {
            text-align: center;
        }
        .header {
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse:collapse
            margin  20px auto;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        .timetable th {
            background-color: #00e1ff4d;
        }
        .timetable td {
            background-color: #2dd3d6d5;
        }
        .subject-table th {
            background-color: #ADD8E6;
        }
    </style>
</head>
<body>
   <center> <img src="/static/WEB_LOGO-01.png" width="1000"</center>
    <h2>Slot Time Table - MANIKANDAN(24900527)</h2>

    <table class="timetable">
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>FREE SLOT</td>
            <td>ENGLISH</td>
            <td>MATHS</td>
            <td>PHYSICS</td>
            <td>ENGLISH</td>
            <td>DIGITAL </td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>MATHS</td>
            <td>DIGITAL</td>
            <td>CAREER</td>
        </tr>
        <tr>
            <td>12-1</td>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>B.EEE</td>
            <td>B.EEE</td>
            <td>MENTOR MEET</td>
            <td>WEB</td>
            <td>PHYSICS</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
        </tr>
    </table>

    <h2>Subject List</h2>

    <table class="subject-table">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19A1414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EY708</td>
            <td>Career development skills (CDS)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>SH3214</td>
            <td>Physics for quantum computing (PQC)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19MA201</td>
            <td>Calculus and matrix algebra (CMA)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EN101</td>
            <td>Communicative engilsh (CE)</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19EE404</td>
            <td>Digital electronics(DE)</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19EE305</td>
            <td>Basic electical,Electronics and measuremant(BEEE)</td>
            <tr>
                <td>8</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor meet (MM)</td>
            </tr>
        </tr>
    </table>
</body>
</html>

```
# OUTPUT
![image](https://github.com/user-attachments/assets/e39744e1-3633-4629-9e9c-ea6984e8d958)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
