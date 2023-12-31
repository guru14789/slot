# Ex03 Time Table
## AIM
To write an HTML webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
## HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
    <head>
<title> SLOT TIMETABLE - SREEKUMAR S (212223240157) </title>
<style>
    table {
           border-collapse: collapse;
           width:70%;
           margin:5px auto;
    }
    table+table
    {
        margin-top: 10px;
    }
    th, td {
        border: 5px solid black;
        text-align: center;
        padding: auto;
    }
    img{
        width:70%;
        display: block;
        margin:auto;
        margin-top: 20px;
        
    }
    .center-text
    {
        text-align: center;
    }
    strong{
        font-weight: bold;
        font-size: 30px;

    }
</style>
</head>
<body>
    <img src="download.png" >
    <div class="center-text">
        <p><strong>
            SLOT TIMETABLE - SREEKUMAR S (212223240157)
        </strong></p>
    </div>
    <table>
        <tr>
            <th colspan="2" bgcolor="yellow">DAY/TIME</th>
            <th colspan="1" bgcolor="Yellow">MONDAY</th> 
            <th colspan="1" bgcolor="yellow">TUESDAY</th>
            <th colspan="1" bgcolor="Yellow">WEDNESDAY</th> 
            <th colspan="1" bgcolor="yellow">THURSDAY</th>
            <th colspan="1" bgcolor="Yellow">FRIDAY</th> 
            
        </tr>
        <tr>
            <th colspan="2" bgcolor="yellow">8-10</th>
            <th colspan="1" bgcolor="cyan">B.EEE</th>
            <th colspan="1" bgcolor="cyan">FOCP</th>
            <th colspan="1" bgcolor="cyan">LA & PP</th>
            <th colspan="1" bgcolor="cyan">FWOT</th>
            <th colspan="1" bgcolor="cyan">LA & PP</th>
        </tr>
        <tr>
            <th colspan="2" bgcolor="yellow">10-12</th>
            <th colspan="1" bgcolor="skyblue">FREE SLOT</th>
            <th colspan="1" bgcolor="cyan">LA & PP</th>
            <th colspan="1" bgcolor="cyan">FOCP</th>
            <th colspan="1" bgcolor="cyan">LA & PP</th>
            <th colspan="1" bgcolor="cyan">B.EEE</th>
        </tr>
        <tr>
            <th colspan="2" bgcolor="yellow">12-1</th>
            <th colspan="5" bgcolor="white">LUNCH TIME</th>
            
        </tr>
        <tr>
            <th colspan="2" bgcolor="yellow">1-3</th>
            <th colspan="1" bgcolor="cyan">FOCP</th>
            <th colspan="1" bgcolor="cyan">FOCP</th>
            <th colspan="1" bgcolor="skyblue">FREE SLOT</th>
            <th colspan="1" bgcolor="cyan">PQC</th>
            <th colspan="1" bgcolor="cyan">SS</th>
        </tr>
        <tr>
            <th colspan="2" bgcolor="yellow">3-5</th>
            <th colspan="1" bgcolor="white"></th>
            <th colspan="1" bgcolor="cyan">PQC</th>
            <th colspan="1" bgcolor="white"></th>
            <th colspan="1" bgcolor="white"></th>
            <th colspan="1" bgcolor="white"></th>
        </tr>
    </table>
     <table>
        <tr>
            <th colspan="2" >S.NO</th>
            <th colspan="3">SUBJECT CODE</th> 
            <th colspan="4" >SUBJECT NAME</th>             
        </tr>
        <tr>
            <th colspan="2" >1</th>
            <th colspan="3">19A1304</th> 
            <th colspan="4" >PYTHON AND LINEAR ALGEBRA</th>             
        </tr>
        <tr>
            <th colspan="2" >3</th>
            <th colspan="3">19A1414</th> 
            <th colspan="4" >FUNDAMENTALS OF WED APPLICATION DEVELOPMENT</th>             
        </tr>
        <tr>
            <th colspan="2" >4</th>
            <th colspan="3">19EE305</th> 
            <th colspan="4" >BASIC ELECTRICAL ELECTRONICS AND MEASUREMENT ENIGNEERING</th>             
        </tr>
        <tr>
            <th colspan="2" >5</th>
            <th colspan="3">19EY701</th> 
            <th colspan="4" >SOFT SKILLS</th>
                        
        </tr>
        <tr>
            <th colspan="2" >6</th>
            <th colspan="3">19PH214</th> 
            <th colspan="4" >PHYSICS FOR QUANTUM COMPUTING</th>
                        
        </tr>
        <tr>
            <th colspan="2" >7</th>
            <th colspan="3">22HS101</th> 
            <th colspan="4" >TAMIL</th>
                        
        </tr>   

    </table>
</body>
</html>
```
## OUTPUT
![Screenshot 2023-12-31 160213](https://github.com/guru14789/slot/assets/151705853/a738157d-edb3-4713-9d4d-27cad2457f18)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
