<!DOCTYPE html>
<html>
<body onresize="myFunction()">

<h4>Resize: onresize</h4>

<p>Try to resize the browser window.</p>

<p id="demo"></p>

	<p>HTML assigns an "onresize" event to the body element and javascript executes it. When the window is resized the height and width change.</p>

<script>
function myFunction() {
    var w = window.outerWidth;
    var h = window.outerHeight;
    var txt = "Window size: width=" + w + ", height=" + h;
    document.getElementById("demo").innerHTML = txt;
}
</script>

</body>
</html>

