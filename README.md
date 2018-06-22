# web-development
<html>
<head>
		<title>ChangeBackground</title>
		<style>
		html
		{
			height: 100%;
			width:100%;
		}
		#background
		{
			height:100%;
			width:100%;
		}
		</style>

</head>
<body>
	<div id="background">&nbsp</div>
	<script>

	function change(i) {  
   var doc = document.getElementById("background");  
   var color =[ "black", "blue", "brown", "green"];  
   for(i=0; i<color.length; i++){  
        doc.style.backgroundColor = color[i];  
        
/*if (i>=color.length){i=0;}*/  
    }
 }  
setInterval(function changebackground(){change(0)},1000);
	</script>
</body>
