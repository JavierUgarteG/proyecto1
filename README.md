<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style type="text/css">
#recuadro1{
    width: 100%;
    height: 100%;
}
body {
    background: white;
    margin: 50px;
}
</style>
<body>
<div id="recuadro1">
     <img src="ps1.png" id="imagen"> <br><br>
     <button onclick="cambioImagen('ps1');">PS1</button>
     <button onclick="cambioImagen('ps2');">PS2</button>
     <button onclick="cambioImagen('ps3');">PS3</button>
     <button onclick="cambioImagen('ps4');">PS4</button>
     <button onclick="cambioImagen('ps5');">PS5</button>
</div>
<script type="text/javascript">
    function cambioImagen(play)
{
    var elemento = document.getElementById("imagen");
    if(play === "ps1"){
        elemento.src = "ps1.png";
    }
    else if(play === "ps2"){
        elemento.src = "ps2.png";
    }
    else if(play === "ps3"){
        elemento.src = "ps3.png";
    }
    else if(play === "ps4"){
        elemento.src = "ps4.png";
    }
    else if(play === "ps5"){
        elemento.src = "ps5.png";
    }
}
</script>
</body>
</html>
