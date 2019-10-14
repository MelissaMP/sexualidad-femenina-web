<!DOCTYPE html>
 <html>
   <head>
     <!--Import Google Icon Font-->
     <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
     <!--Import materialize.css-->
     <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>

     <!--Let browser know website is optimized for mobile-->
     <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
   </head>

   <body id="cuerpo">
      <a class="btn" id="botoncito"> buttton </a>
      <p id="parrafito">hola soy un parrafo </p>
      <img id="chuchu" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRXONgqOQIKAHqTZrhNeaPCowd0QpbEIlTtyoazCoGR6sqWh80Jtw">
      <div class="card-panel teal lighten-2">This is a card panel with a teal lighten-2 class</div>
      <div class="card-panel pink accent-2">This is a card panel with a teal lighten-2 class</div>

    <div class="row deep-orange lighten-5">
      <div class="col s3 "><img class="circle responsive-img" src=""></div>
      <div class="col s9  ">Titulo</div>

  </div>

     <!--JavaScript at end of body for optimized loading-->
     <script type="text/javascript" src="js/materialize.min.js"></script>
     <script type ="text/javascript">
      document.getElementById("botoncito").addEventListener("click",ir);
      function ir (){
         //alert("Eres el visitante 3000 ganaste un iphone de 35 mil pesos");
          document.getElementById("chuchu").setAttribute("src","https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQc1zyzUkP5CSENslJXcJ3-ZufBZMdV3dKuAUPQqeloc8ddDnE7");

       }
       document.getElementById("parrafito").addEventListener("click",mostrar);
       function mostrar(){
         //alert("ese es un parrafo");
         document.getElementById("cuerpo").setAttribute("class","fondo");

       }



       </script>
   </body>
 </html>
