# My-New-Calculetor--Version-3
This is so Amazing Calculator App Version-3.



<!DOCTYPE html>
<html> 
<head> 
<title>
    Calculator Version 3
</title>
<link href='https://fonts.googleapis.com/css?family=Orbitron' rel='stylesheet' type='text/css'> 
</head>

<style>
*{
  margin:0px;
  padding:0px;
  font-family: 'Orbitron', arial; 
}
body{
  background-color:#EEEEEE;
  background-size:cover;
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  Flex-direction:column;
}
form{
  background-color:#223322;
  position:relative;
  width:80%;
  top:10px;
  padding:20px;
  border:1px transparent;
  border-radius:25px;
  box-shadow: -7px -7px 20px 0 rgba(255, 255, 255, 0.2), 7px 7px 20px 0 rgba(0, 0, 0, 0.3);
}

input[type="button"]{
  width:90%;
  height:400%;
  color:white;
  background-color:#000000;
  border:none;
  outline:none;
  font-size:30px;
  border-radius:5px;
  box-shadow: -7px -7px 20px 0 rgba(255, 255, 255, 0.2), 7px 7px 20px 0 rgba(0, 0, 0, 0.3);
}
input[type="text"]{
  width:90%;
  height:50px;
  font-size:25px;
  background-color:#A9A75B;
  border:1px solid transparent;
  position:relative;
  margin-bottom:10px;
  border-radius:10px;
  color:black;
  padding-left:10px;
  box-shadow: -7px -7px 20px 0 rgba(255, 255, 255, 0.2), 7px 7px 20px 0 rgba(0, 0, 0, 0.3);
  
  
}
P{
    color:black;
    position:absolute;
    bottom:0px;
    Font-size:10px;
}
#equals
{
  width:90%;
  height:400%;
  color:white;
  background-color:#87CEEB;
  border:none;
  outline:none;
  font-size:30px;
  border-radius:5px;
  box-shadow: -7px -7px 20px 0 rgba(255, 255, 255, 0.2), 7px 7px 20px 0 rgba(0, 0, 0, 0.3);
}

#clear 
{
  width:90%;
  height:400%;
  color:white;
  background-color:#FFA500;
  border:none;
  outline:none;
  font-size:30px;
  border-radius:5px;
  box-shadow: -7px -7px 20px 0 rgba(255, 255, 255, 0.2), 7px 7px 20px 0 rgba(0, 0, 0, 0.3);
}
#cut
{
  width:90%;
  height:400%;
  color:white;
  background-color:#FFA500;
  border:none;
  outline:none;
  font-size:30px;
  border-radius:5px;
  box-shadow: -7px -7px 20px 0 rgba(255, 255, 255, 0.2), 7px 7px 20px 0 rgba(0, 0, 0, 0.3);
}
</style>
<body> 
<form name="cal"> 
<table align = "center"> 
<tr> 
<td colspan="4"> 
<input type="text" name="displ" id="display" disabled> 
</td> 
</tr> 
<tr> 
<td>
<input type="button" name="one" value="1" onclick="cal.display.value += '1'">
</td> 
<td>
<input type="button" name="two" value="2" onclick="cal.display.value += '2'">    
</td> 
<td>    
<input type="button" name="three" value="3" onclick="cal.display.value += '3'">    
</td> 
<td>    
<input type="button" class="operator" name="plus" value="+" onclick="cal.display.value += '+'">
</td> 
</tr> 
<tr> 
<td>    
<input type="button" name="four" value="4" onclick="cal.display.value += '4'">    
</td> 
<td>    
<input type="button" name="five" value="5" onclick="cal.display.value += '5'">
</td> 
<td>    
<input type="button" name="six" value="6" onclick="cal.display.value += '6'">
</td> 
<td>
<input type="button" class="operator" name="minus" value="-" onclick="cal.display.value += '-'">
</td> 
</tr> 
<tr> 
<td>
<input type="button" name="seven" value="7" onclick="cal.display.value += '7'">
</td> 
<td>
<input type="button" name="eight" value="8" onclick="cal.display.value += '8'">
</td> 
<td>
<input type="button" name="nine" value="9" onclick="cal.display.value += '9'">
</td> 
<td>
<input type="button" class="operator" name="times" value="x" onclick="cal.display.value += '*'">
</td> 
</tr> 
<tr> 
<td>    
<input type="button" name="dot" value="." onclick="cal.display.value += '.'">

</td> 
<td>
<input type="button" name="zero" value="0" onclick="cal.display.value += '0'">
</td> 
<td>
<input type="button" id="equals" name="equals" value="=" onclick="try{cal.display.value = eval(cal.display.value);}catch(err){cal.display.value = 'Error';}">
</td> 
<td>
<input type="button" class="operator" name="div" value="/" onclick="cal.display.value += '/'">
</td> 
</tr> 
<tr> 
<td colspan="2">    
<input type="button" id="doublezero" name="doublezero" value="00" onclick="cal.display.value += '00'">
</td> 
<td>
<input type="button" id="clear" name="clear" value="c" onclick="cal.display.value = ''">
</td> 
<td>
<input type="button" id="cut" name="cut" value="&lt-" onclick="cal.display.value = (cal.display.value).substring(0, (cal.display.value).length-1)">
</td> 

</tr> 
</table> 
</form> 
<p>Copyright 2021 &copy; Mjahid Ansari</p>
</body> 
</html>
