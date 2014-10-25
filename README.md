TypeWriter
==========

With TypeWriter you can add a real time typing effects for for web page. It very simple and effecttive.



=============================
TypeWriter is a PURE JAVASCRIPT Plugin

How to make it work:
1)Include the TypeWriter.js file at the <head> section of your code
2)Call the function typewriter(str,location,min,max);
3)Now TypeWriter will do it's magic

This is a initial version. More options to be included later...



======================
Function Call Explained:

typewriter(str,location,min,max);
"str" is the string on which the typewriter has to work.
"location" is the place in your html where the result from the plugin has to br displayed.
"min" "max" are the minimun and maximum time delays. So,within the range of the min and max the time delay for each character 
will occur.

========================
Example:
<html>
<head>
<script src="TypeWriter.js"></script>
<body>
<p id="insert"></p>
<script>
var str = "TypeWriter is AWESOME";
var location = document.getElementById("insert");
typewriter(str,location,200,400);
</script>
</body>
</html>
========================
for any queries contact me at talkto@praneshravi.in
for more of my works visit http://praneshravi.in
