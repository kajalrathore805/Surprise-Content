<!DOCTYPE html>  
<html>  
<head>  
<meta charset="utf-8">  
<title>jQuery UI addClass Example</title>  
 
<script src="http://code.jquery.com/jquery-1.10.2.js"></script> 
<script src="http://code.jquery.com/ui/1.10.4/jquery-ui.js"></script>  

 

<script>  
$(document).ready(function() {  
$('#one').click(function() {  
$(this).animate({  
  height:"90%",
  width:"90%"  
});  
 });
});  
</script>  


</head>  
<body>  
<center><img id="one" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOsRRkgcESCY3MBh-pAnOVLUCPRfChiBLBOg&s" width="1%" height="1%" onclick="fun()">  
<p>Please click this image</p>
</center>

<audio id="two">
  <source src="ghost.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
<script>
function fun()
{
x=document.getElementById("two");
x.play();
}
</script>
</body>  
</html>
