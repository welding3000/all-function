# all-function

// Este es un estilo Css

    div{
    background-color:#D94A38;
    width:90px;
    height:20px;
    padding:40px;
    }
// creamos la estructura en html

    // Aqui llamamos un onmousedown|  onmouseup
         <div onmousedown="down(this)" onmouseup="up(this)" >Click Me</div>

    // Aqui llamamos un onmouseover | onmouseout
          <div onmouseover="over(this)" onmouseout="out(this)"
// Llamamos la function down y agregamos un parametro() 

    function down(obj) {
        obj.style.backgroundColor = "#1ec5e5";
        obj.innerHTML = "Release Me";
    }
// llamamos  over | out

    // llamamos un function over(this) 
          function over(obj) {
              obj.innerHTML = "Thank You"
          }
    // llamamos un out()
          function out(obj) {
              obj.innerHTML = "Mouse Over Me"
          }
// Llamamos la function up y agregamos un parametro() 

    function up(obj) {
        obj.style.backgroundColor="#D94A38";
        obj.innerHTML="Thank You";
    }
-------------------------------------------

// llamando una function valor()

    function my() {
         /* estamos buscando la etiqueta P para llamarla*/
    var list = document.getElementsByTagName("p");
         /* creamos una variable para poderla llamar*/
    var i;
        /* llamamos a la variable list  */
    for (i = 0; i < list.length; i++) {
        list[i].style.backgroundColor = "red";
      }
    }
















