# Second-Task
<!--HTML Forms Task-->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Second-Task</title>

</head>

<body>
<h3>Registration Form !</h3>

<form >
    <h4>Personal details</h4>
    <hr>
    <br>
   <div>

    <label for="first">First name :</label>
    <input id="first" type="text>">

   </div>
   <br>
   <div>
    <label for="Last">Last name :</label>
    <input id="Last" type="text>">

   </div>
   <br>
   <div>
    <label for="Email">Email :</label>
    <input id="Email" type="email">
     
   </div>
   <br>
   <div>
    <p>Gender:
    <input id="Male" type="radio" name="Gender">
    <label for="Male">Male</label>
    <input id="Female" type="radio" name="Gender">
    <label for="Female">Female</label>
    </p>
   </div>

   <div>
    <label for="Cty">City :</label>
     <select name="Cty" id="Cty">
        <option value="Amman">Amman</option>
        <option value="Zarqaa">Zarqaa</option>
        <option value="Irbid">Irbid</option>
        <option value="Aqaba">Aqaba</option>
     </select>

   </div>
   <br>
<input type="button" value="Sign up">
</form>

</body>

<html>

---
<!--HTML List Task-->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Second-Task</title>

</head>

<body>
<h4>What about Back-end ?</h4>

<ul>
   <li type="square">Back-end</li>
   <ol type="i">
      <li>Python</li>
      <li>PHP</li>
      <Ol type="A" reversed start="26">
         <li>Laravel</li>
         <li>Pure</li>
      </Ol>
   </ol>

</ul>

</body>

<html>
---
<!--HTML Tables Task-->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Second-Task</title>

</head>

<body>
<h4>Table Num. 2</h4>

<table border="1">
   <tr>
      <td rowspan="2">Row 1-2, Col 1</td>
      <td>Row 1, Col 2</td>
      <td>Row 1, Col 3</td>
      <td>Row 1, Col 4</td>
   </tr>
   <tr>
      
      <td rowspan="2" colspan="2">Row 2-3, Col 2-3</td>
         <td>Row 2, Col 4</td>
   </tr>
   <tr>
      <td>Row 3, Col 1</td>     
      <td>Row 3, Col 4</td>
   </tr>
   <tr>
      <td>Row 4, Col 1</td>
      <td>Row 4, Col 2</td>
      <td colspan="2">Row 4, Col 3-4</td>
   
   </tr>

</table>

</body>

<html>