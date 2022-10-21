<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Nobia</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: pink;
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('Eres el amor de mi vida <3, la princesa de mis ojos, enserio perdoname mi cosita chiquita, te adoro mi cielito, eres lo mas importante en mi vida');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "30px";
            document.getElementById('btnNo').style.top = newHeight + "30px";


        }
    </script>
</head>
<body>
    <h3>Me perdonas solecito de mi vida?</h3>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <center><img src="chuec.png" width="400"></center>
</body>
</html>
