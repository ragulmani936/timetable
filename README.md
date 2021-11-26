# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
	
   <body>

      <table border = "1" cellspacing="1" bordercolor="blue" bgcolor="yellow">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
            <th colspan="2">Reference Number:</th>
            <th colspan="2" align="left">21500303</th>
            <th colspan="2">Name:</th>
            <th colspan="2" align="left">Ragul M</th
         </tr>
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
             <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
         </tr>
        
         <tr>
             <td>MONDAY</td>
             <td colspan="2">-</td>
             <td colspan="2">Linear algebra</td>
             <td>lunch break</td>
             <td colspan="2">Mathematics for AI</td>
             
         </tr>
         <tr>
             <td>TUESDAY</td>
             <td colspan="2">Web technology</td>
             <td colspan="2">Engineering design</td>
             <td>lunch break</td>
             <td colspan="2">Engineering mechanics</td>
             
         </tr>
         <tr>
             <td>WEDNESDAY</td>
             <td colspan="2">Fundamental of web technology</td>
             <td colspan="2">Mthematics for AI</td>
             <td>lunch break</td>
             <td colspan="2">-</td>
             
         </tr>
         <tr>
             <td>THURSDAY</td>
             <td colspan="2">Engineering mechanics</td>
             <td colspan="2">Python programming</td>
             <td>Mentoring</td>
             <td colspan="2">Engineering design</td>
             
         </tr>
         <tr>
             <td>FRIDAY</td>
             <td colspan="2">Fundamental of web technology</td>
             <td colspan="2">Python programming</td>
             <td>lunch break</td>
             <td colspan="2">Soft skills</td>
             
         </tr>
      </table>
      
   </body>
</html>



~~~
# OUPUT
<!DOCTYPE html>
<html>

   <head>
       <title>TIME TABLE</title>
   </head>
	
   <body>

   <table border = "2" cellspacing="1" bordercolor="yellow" bgcolor="blue">
<img src="logo.png">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
            <th colspan="2">Reference Number:</th>
            <th colspan="2" align="left">21500303</th>
            <th colspan="2">Name:</th>
            <th colspan="2" align="left">Ragul M</th
         </tr>
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
             <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
         </tr>
         <tr>
             <td>MONDAY</td>
             <td colspan="2">-</td>
             <td colspan="2">19MA221 Linear algebra</td>
             <td>lunch break</td>
             <td colspan="2"> 19MA220 Mathematics for AI</td>
         </tr>
         <tr>
             <td>TUESDAY</td>
             <td colspan="2">19AI402 Web technology</td>
             <td colspan="2">19AI302 Engineering design</td>
             <td>lunch break</td>
             <td colspan="2">19AI303 Engineering mechanics</td>
         </tr>
         <tr>
             <td>WEDNESDAY</td>
             <td colspan="2">19AI401 Fundamental of web technology</td>
             <td colspan="2">19MA220 Mthematics for AI</td>
             <td>lunch break</td>
             <td colspan="2">-</td>
         </tr>
         <tr>
             <td>THURSDAY</td>
             <td colspan="2">19AI303 Engineering mechanics</td>
             <td colspan="2">19AI301 Python programming</td>
             <td>ECA051-AD Mentoring</td>
             <td colspan="2">19AI302 Engineering design</td>
         </tr>
         <tr>
             <td>FRIDAY</td>
             <td colspan="2">19AI401 Fundamental of web technology</td>
             <td colspan="2">19AI301 Python programming</td>
             <td>lunch break</td>
             <td colspan="2">19EY701 Soft skills</td>
         </tr>
      </table>
      
   </body>
</html>