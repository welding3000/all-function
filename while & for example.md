# all-function
  
          var trabajador= new Array();  // array indefinido
          var persona = "";             // string sin contenido
          var  contar = 0;              // empesamos a contar

/* creamos un variable*/

      while( persona != "salir" ){                   // llamamos a [""] var persona  !=  oprimir salir
            persona = prospt('introduce nombre ');   // almacenamos los nombres =  escribimos nombres alert prompt 
            trabajador[contar] = persona;            // trabajado se va almacenando los array en la variable 
                                                     // [contar] va cambiando la numeracion y añadiendo 1 ++ 
                                                     // persona va almacenando tus nombre
          contar++     
        }
/* que no salga sali se agrega el siguiente comando*/
      
      trabajador.pop();     // sirve al final para no poner salir al final y no aparesca en print

      for( i = 0; i < trabajador.length; i++ ){      // llamamos a trabajador y como no sabemos la [].length  
          document.write(trabajador[i] + '<br>' );   // llamamos a trabajador [i] 

      }


--------------------------------------------------------------------
The do...while Loop

// Dentro de una variable almacenamos los dias | en otra contamos desde 0 

    var dia =['lunes','martes','miercole','jueves','viernes']
    var i = 0 ;

// do | llamamos la sentencita y el incrementp

    do {
      document.write( dia[i] +'<br />');
       i ++
    }
// while solo damos la orden de i[0] < dia[]; 
    
    while( i < dia.length );

--------------------------------
      
      
  
  
  
  
  
  
  
  
  
  
