# Moises-Vanegas
!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>mi formulario</title> 
	<style>
		.estilo{
              width: 400px;
	          height: 300px;
	          top: 500px;
	          left: 200px;
	          font-size: 15px;
	          background: red;
	          color: black;
	          border: solid;
	          border-color: black;
	          border-radius: 10px;
		}
		.n{
			position: absolute;
		left: 10px;
		top: 100px;	
		}
		.w{
			position: absolute;
		left: 10px;
		top: 150px;	
		}
		.p{
			position: absolute;
		left: 10px;
		top: 200px;	
		}
		.boto{
			position: absolute;
			top: 150px;
			left: 200px;
			width: 90px;
	        height: 20px;
	        border: solid;
	        border-color: black;
	        border-radius: 10px;
		}
		.hola{
			position: absolute;
			top: 250px;
			left: 10px;
		}
	
	
	</style>
</head>
<body>
	<div class="estilo">
	<div class="n"></div>
	<div class="e">Tenemos papas a(3500)</div>
	<div class="i">Tenemos doritos a(1500)</div>
	<div class="q">Tenemos chocolatina a(2500)</div>
	</div>

	<div id="papas"></div>
	<div id="doritos"></div>
	<div id="chocolatina"></div>
	<div id="o"></div>
	<div id="v"></div>
	<div id="r"></div>

<form>
	    <input class="n" type="text" name="dato" placeholder="Compra">
      <input class="w" type="text" name="dato2" placeholder="Cantidad">
        <input class="p" type="text" name="dato3" placeholder="Mi Dinero">
	



				
				<div class="boto" onclick="calcu()" id="boton"> Proseso</div>
		


		
		<script >
	function calcu(){
	o=Number(datos.value)
     
	v=Number(dato2.value)
    r=Number(v*3500)

	
	
	boton.innerHTML="compraste " + dato + "y tu cuenta es "+ r ;
if(dato==papas)    
{
r=v*3500
m=r-3500
}


if(dato==doritos)
{
r=v*1500
m=r-1500
}

if(dato==chocolatina)
{
r=v*2500
m=r-2500
}


</form>

</body>

</html>
