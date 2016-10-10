# all-function
# function-javastript

// vamos a ver una serie de comandos para aplicar

// esto sive para cambiar el contenido

    document.getElementById("demo4").innerHTML = " changed con fuction";

/*Oculta contenido */

    document.getElementById('p1').style.visibility='hidden'
/* visible el contenido */
    
    document.getElementById('p1').style.visibility='visible'

// Aumenta el tamaño de la letra

    document.getElementById('demo5').style.fontSize='35px';  

// se puede agregar estilos dentro document.

    function variable(){
    var x= document.getElementById('demo9');
        x.style.color='white';
        x.style.background='black';
        x.style.border='1px solid white';
    }


---------------------------------------------------
// se puede multiplicar dividir
  hay 3 formas

        string
        number
        booleans

// DENTRO DE UNA VARIABLE

    var a = 3; var x = (100 + 50) * a;

// otro ejemplo

    var x = 5; var y = 6; var z = x + y;

// suma de variable

        var x = 5; var y = 6; var z = x + y;

/* resta*/
    
    var x = 5; var y = 6; var z = x - y;
/* multiplicacion*/
    
    var x = 5; var y = 6; var z = x * y;
/*divicion*/
    
    var x = 5; var y = 6; var z = x / y;




----------------------------------------------------
// Se utiliza comúnmente para controlar sentencias de flujo  if,for,while

    var i =3;
    while( i< 5){
      document.write('hola como estas ');
     i++
    }


// for tres expresiones opcionales,separadas por puntos y comas

    for( i=3; i<5; i++ ){
      document.write('Hola word ');
    }


// If sirve para confirmar
/* este if confirma verdadero y falso es un tipo booleano*/

    function verdadero(){
       if(5 == 6){
      document.write('verdadero');
    }else{
      document.write('falso');
     }
    }

/* Este ejemplo añadimos un else if podemos agregar cuantas sentencias nesecitemos*/

    function o(play,distance){
        if( distance <= 10 && distance > 0 ){
            document.write( play + ' numeracion  ');
      }   
      else if( distance <= 0 ){
            document.write( play + ' struck today  ');
      }
      else{  
            document.write( play + ' Error falso final  ');}
    }
    o('miguel' , 0);

// ejemplo de if 

    var greeting;
    var time = 88;
          if (time <= 10) {
          greeting = "Son iguales"; 
          } 
          else if ( time >= 18 && time <= 35 ) {
          greeting = "Eres joven"; 
          }
          else if ( time >= 36 && time < 66 ) {
          greeting = "Eres viejo"; 
          }
          else if ( time > 86 ) {
          greeting = " viejo"; 
          }
          else { 
          greeting = "Error";
          }
    document.getElementById("mayor").innerHTML = greeting;


/* switch*/

    var dia = 'viernes';
    switch(dia){
     case 'lunes':
       document.write('hoy lunes')
     break;
     case 'viernes':
       document.write( 'hoy martes https://www.youtube.com/watch?v=YaE72TmSg68') 
     break;
     default:
        document.write('Invalid moon phase');
     break;
    }






-----------------------------------------
// Function  secuencia
/* aque estamos agregando un parametro dentro de function */

    function saludos(nombre,edad){
         document.write('Hola me llamo '+ nombre + ' tengo  ' + edad + 'años de edad');
    }
      saludos('Miguel ',15); 

/* parametro para realizar valores numericas*/

    function add(x,y){
        result =x*y
       document.write(result);
    }
    add(4,4)


    function ad(x,y){
      result =x*y
       return result;
    }
    var resultado= ad(3,4);
    document.write(resultado);


/* Aprender a llamar funciones una dentro de otra */

    var x = ' Este es mi numero:';
    function uno(){ document.write(  'Este es mi numero:');}
    function dos() { document.write( 'llamando al 2'); }
    function tres(){ document.write( ' llamando 3 ' + ' <hr>');}
       function llamando(){
         uno();
         dos();
         tres();
       }
    llamando();

-----------------------------------------------------


// creamos una array 

    var frutas=[' manzana ',' pera ',' cereza ']
               var seleccionarFrutas=frutas[1];
               document.write(seleccionarFrutas);

// second function 
 // añade una variable dentro de llaves almacena todo y escrive . 

        var time = { 
        strick : 'miguel', 
        edad : 21, 
        boolean : 'false',
        };
           document.write( time.edad);

        var i = {
        strick : 'miguel',
        edad : 21, 
        boolean : 'false',
        };
         var añade = i.edad +2 ;  
         document.write( añade);




// crear un rolover
    
    
    // onclick
    
/* Este parametro se añade en html y crear una alerta cada ves al 
   mouse se retire de un button ahy  aparecera una alerta
*/

    //onmouseout

/* Este parametro se añade en html y crear una alerta cada ves al 
   mouse se hacerca de un button ahy  aparecera una alerta
*/

    // onmouseover




// Agregar una functio numerica

        function fraccion(añade,multiplica){
           var total = añade *( 1+(multiplica/100))   ;
           return total;
        }
        var final = fraccion(450,20) ;
        document.write(final);


// interactuar con el usuarip

    // confirm = va a sacar 2 valores aceptar o cancelar
    // alert = cuadro de alerta
    // prompt = poder escribir dentro de una alerta
    
    var result = confirms('ola');










