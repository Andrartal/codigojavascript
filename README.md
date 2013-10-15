codigojavascript
================

 generacion de codigo 
<!DOCTYPE html>
<html language="es">

<head>
<title>El Genero Musical </title>
</head>

<body onload="Generar()">
<div id="web">
</body>
</html>

<script type="text/javascript">
function Generar() 
{
var cont="";
cont="<form>";
cont+="<div>Buscar:>input type='text'  name='Busqueda'  onchange='ValidarBusqueda(form.Busqueda.value)";
cont+="  </div><br>"
cont+="</form>"

cont+="<center>"
cont+="<label>Nombre de Usuario/Correo Electrónico:</label>"
cont+="<input type='text' name='user' ><br>"
cont+="<label>Contraseña:</label>"
cont+="<input type='Password' name='pass'></br>
cont+="<input type='Button' name='BotonEntrar' value='Entrar' onclick='valida(pass.value)'>"
cont+="</center>"

cont+="<header>"
cont+="<hgroup><h1>Lo Mejor Del Genero Musical</h1>"
cont+="</hgroup>"
cont+"</header>"

cont+="<nav>"
cont+="<ul>"
cont+="<li>Lo mas reciente</li>"
cont+="<li>Nuevas Musicas</li>"
cont+="<li>Artistas</li>"
cont+="<li>Letras de canciones</li>"
cont+="<ul>"
cont+="</nav>"

cont+="<div id='main'>"
cont+="<div id='Escucha tu musica favorita, ya sea regueton, baladas, bachatas, pop, musica electrónica y mucho mas '>"
cont+="<section>"
cont+="Noticias Nacionales"
cont+="<article>"
cont+="<header> <h3>Noticia 1</h3></header>"

cont+="<div>"
cont+="<p>El próximo 17 de octubre Quito acogerá un concierto en el que se presentarán dos populares grupos latinoamericanos, los mexicanos Molotov y los uruguayos Cuarteto De Nos. Molotov es una de las formaciones más rebeldes del rock latino con una popularidad que ha traspasado las fronteras de América y un estilo que fusiona distintos géneros.</p>"
cont+="</div>"

cont+="<footer> </footer>"
cont+="</article>"
cont+="<hr/>"
cont+="<article>"
cont+="<header> <h3>Noticia 2</h3></header>"

cont+="<div>"
cont+="<p>Este sábado 5 de octubre se llevará a cabo en los bajos del Palacio Municipal una actución de los veteranos músicos Pacheco & Napolitano, que contarán con el apoyo de Bilo Albán y Jairo Vargas, de Batukka, Lalo Wong y otros músicos que pasarán por el escenario. </p>"
cont+="</div>"

cont+="<footer> </footer>"
cont+="</article>"
cont+="</section>"

cont+="<section>"
cont+="Noticias nternacionales"
cont+="</section>"
cont+="<article>"
cont+="<header> <h3>Noticia 3</h3></header>"

cont+="<div>"
cont+="<p> Los reguetoneros Wisin y Yandel  se separan y lo hacen con un concierto en la capital. La presentación será el sábado, a las 21:00, en el coliseo General Rumiñahui.

El dúo puertorriqueño es la atracción principal de la noche de fiesta denominada Urban Fest Platinum 6 2013. Nueve exponentes del reguetón ecuatoriano forman parte de la cartelera que abrirá el concierto principal. </p>
</div>"

cont+="<footer> </footer>"
cont+="</article>"
cont+="<hr/>"
cont+="<article>"
cont+="<header> <h3>Noticia 4</h3></header>"
cont+="<div>"
cont+="<p>La performance de Miley Cyrus en los Video Music Awards 2013 dio mucho que hablar. Pero hay voces más autorizadas que otras. Para eso, por ejemplo, está Cyndi Lauper, que conoce a la ex Hannah Montana y tiene bastante experiencia en el rubro.</p>"
cont+="</div>"

cont+="<footer> </footer>"
cont+="</article>"

cont+="</div>"

cont+="<audio controls >"
cont+="<source src="C:/Users/User/Documents/Carpeta de Andrés/mp3/Daddy Yankee Ft. Wisin Y Yandel - Limbo (Official Remix) (Www.FlowActivo.Com).mp3"  type="audio/mp3" >"
cont+="</audio>"


cont+="<h2>Video musical</h2>"
cont+"<div style='text-align: center'>"
cont+="<video src='C:/Users/User/Documents/Carpeta de Andrés/Video/Wisin & Yandel- Algo Me Gusta De Ti ft Chris Brown ft T Pain.mp4'  controls=''  poster='C:/Users/User/Documents/Carpeta de Andrés/Video/Poster.png'width='900px'  height='480px'  type='video/mp4'  >" 
cont+="</video>"
cont+="</div>"

cont+="</div>"
cont+="<footer>"
cont+="<span>Facebook  Twitter  Gmail</span>"
cont+="</footer>"

document.getElementById("web").innerHTML=cont;
}

function ValidarBusqueda(valor)
{
if(/^[a-z-A-Z\D]+$/. test(valor))
{
alert(valor+" este dato si existe")
return(true)
}
else
{
alert(valor+" este dato no existe")
return(false)
}
}

function valida(user){
if(/([a-z+A-Z+0-9]{8})/.test(user)){
alert('Ingresando');
}else{
alert('Error');
}
}

function valida(pass){
if(/([a-z+A-Z+0-9]{8})/.test(pass)){
alert('Ingresando');
}else{
alert('Error');
}
}
</script>
