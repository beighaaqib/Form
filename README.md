# Form
form using HTML CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>form </title>
</head>
<form action="" method="get"></form>


<body style="background-image:url(download.jpeg)" >
  <!-- <img src="download.jpeg" alt="" style="width: 550px; height:800pxS"> -->
    <h1 style ="color: rgb(0, 17, 255);text-align: center; " >My form</h1>
    
   <div style="color:blue; text-align: center;" >
        date: <input type="date" name="date">
 </div><br>
  <div style="color:red; text-align: center;"> 
       Name : <input type="text" name="name" id="name"></div> <br>
   <div style="color: blue ;text-align: center">
     Adress : <input type = "text" name = "address">
</div><br>
<div style="color: yellow;text-align: center">
     Are you eligible : <input type ="checkbox" name="eligible">
</div><br>
<div style="color:aquamarine;text-align: center">
    <select>
        <option name ="gender">choose</option>
       <option value = "male">male</option>
       <option value = "female">Female</option>
       <option value = "other">other</option>
    </select>
</div> <br>

    <div style = "color:orange;text-align: center">
        <input type ="radio" name="category" value="general">General
        <input type="radio" name="category"value=obc>obc
        <input type="radio" name="category"value=sc>sc
    </div> <br>
        
<div style="color: rgb(235, 11, 29);text-align: center">
     email: <input type ="email"name="myemail">
    </div> <br>
<div style="color: rgb(66, 0, 248);text-align: center;">
     write about yourself:<br> <textarea type ="text" name="mytext"cols="30" rows="10"></textarea>
</div> <br>
<div>
    <button type ="submit " value="submit" style="background-color: blue; ">Submit</button> 
    <button type ="reset " value="Resetnow" style=" background-color: violet; ">Resetnow </button>
</div>
    



</body>
</html>
