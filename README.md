<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Calculating D</title>
</head>
<body>
    <script>  
        function showResult() 
        {
            console.log("showResult - begin");
            var a = parseInt(document.getElementById('a').value, "10");
            var b = parseInt(document.getElementById('b').value, "10");
            var c = parseInt(document.getElementById('c').value, "10");
            var x = parseInt(document.getElementById('x').value, "10");
            var discriminant = b**2-c*a*4;
            var solution=discriminant**0.5;
            var x = solution

            console.log("disc " +discriminant, "sol  "+solution );
            
        }
    </script>
    
    a - <input type="text" id="a" name="a" />
    b - <input type="text" id="b" name="b" />
    c - <input type="text" id="c" name="c"  />
    x - <type="text" id="x" name="x"  />
    <input type="submit" onclick="showResult()" value="Result" />

</body>
</html>
