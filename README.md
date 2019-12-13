<h1><em>Esrephanie Quiros</em></h1>
<p><img src="https://scontent.fpac1-1.fna.fbcdn.net/v/t1.0-9/80087353_511817432765879_7017483808656064512_n.jpg?_nc_cat=111&_nc_ohc=V04QUe0xRRAAQmRMXHyHUkOecwf5LwOebmEWQXgCqJNzWLgVgFxqx74Jw&_nc_ht=scontent.fpac1-1.fna&oh=cd95b501a87b2ee5c34b96ec616df49c&oe=5E6CD7AF">    
<h1><p><strong><a href="https://estephanie-quiros.github.io/Formulario-de-datos/">Formulario de datos</a></strong></h1>
<p><em> Nombre Completo:</em>   Estephanie Quiros  
<p><em>Fecha Nacimiento:</em>    17 de febrero de 2001
<p><em>Edad:</em>   18 años
<p><em>Nacionalidad:</em>  Panameña
  
<h1>Datos Educativos</h1>
<p><strong>Escuelas:</strong><p>
<p><em>- Primaria: Las Paredes </em>
<p><em>- Premedia y media: Colegio Rodolfo Chiari </em>
<p><strong>Universidad:</strong>
<P><em>- Universidad Nacional de Panamá</em>
<h1>Redes Sociales</h1>
<p><strong>Instagram:</strong> <a href="https://www.instagram.com/estephanie.1707/">estephanie.1707</a>
<p><strong>facebook:</strong> <a href="https://www.facebook.com/fefyquiros/">fefyquiros</a>                  

>
<p>Geolocalización</p>
<button onclick="getLocation()">Try It</button>

<p id="demo"></p>

<script>
var x = document.getElementById("demo");

function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.watchPosition(showPosition);
  } else { 
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}
    
function showPosition(position) {
    x.innerHTML="Latitude: " + position.coords.latitude + 
    "<br>Longitude: " + position.coords.longitude;
}
</script>

</body>
</html>
