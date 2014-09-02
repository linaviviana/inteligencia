inteligencia
============

inteligencia artificial
<html>
<head>
</head>
<body>

<script type="text/javascript">
  function ingresar(numeros)
  {
    	var l;
    	var num = 0;
  		var i;
  		var j;
  		var cont=0;
  		document.write('lista <br>');
    			for(l=0;l<numeros.length;l++)
    			{
    			numeros[l]=parseInt(v);
    					var v;
      				v=prompt('Ingrese numero:','');
      			for(j=0;j<numeros[l];j++){	 
      						if(numeros[l]%j==0){
      							cont=cont+1;
      					}
      			}
      			
 			if(numeros[l]%2==0) {
 			if(cont!=2){
						document.write('no es primo');
	     				}
	     				else {
	     				document.write('es primo');
	  
	     				} 	
      						        document.write('par ',numeros[l],'<br>');    	
      			}
    				else {
    		if(cont!=2){
								document.write('no es primo');
	     				}
	     				else {
	     				document.write('es primo');
	  
	     				} 	
      									document.write('impar',numeros[l],'<br>');
  					}	
    			}	   							
   
  
     
   } 
   

  
  
  	
   
  
  var numeros;
  numeros=new Array(5);
  ingresar(numeros);
  esPrimo(num);
 
  
  </script>

</body>
</html>
