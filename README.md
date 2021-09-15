![aaaaa](https://user-images.githubusercontent.com/90706129/133510199-6739dba0-d873-4bea-a88d-8bb0df459d6e.png)
# prueba-tecnica
desarrollo angular
installe angular

npm install -g @angular/cli

verifico versiones ng -v

creo el proyecto ng new PruebaTecnica

voy al directorio cd PruebaTecnica

instalo bibliotecas de angular

Instalamos dependencias necesarias desde el “NPM”, lo primero que tenemos que hacer es ir a 
nuestra consola y tipear lo siguiente.

npm install bootstrap jquery @popperjs/core

Luego de eso nos dirigimos al archivo “angular.json” y colocamos las siguientes instrucciones en 
los objetos “styles” y “scripts” en donde llamaremos a las propiedades css del bootstrap y las 
dependencias scripts correspondientes a las interacciones de cada uno.

"styles": [
 "node_modules/bootstrap/dist/css/bootstrap.min.css",
 
 "src/styles.scss"
],

"scripts": [

 "node_modules/jquery/dist/jquery.min.js",
 
 "node_modules/@popperjs/core/dist/umd/popper.min.js",
 
 "node_modules/bootstrap/dist/js/bootstrap.min.js"
 
]

Voy a index html y comienzo a configuarar a mi gusto

<!doctype html>
<html lang="en">
<html lang="en">


  <html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
 


    <meta charset="utf-8">

    <link rel="stylesheet" href="nuevo.css"/>
    <link rel="stylesheet"     href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
    <link href='https://fonts.googleapis.com/css?family=Libre+Baskerville' rel='stylesheet' type='text/css'>
    <title>prueba</title>
  </head>
  <body>
    <div class="container-fluid">
      <br>
      <ol class="breadcrumb">
        <li><a href="#">inicio</a></li>
        <li><a href="#">marvel</a></li>
        <li><a href="#">dc</a></li>

      </ol>
    </div>
     <div class="container-fluid">
      <div class="row">
        <div class="col-md-2">
          <img src="C:\Users\jekaf\PruebaTecnica\src" class="img-responsive img-rounded" alt="">
        </div>
      </div>
    </div>

    <div class="container-fluid">
      <br>

      </div>
      <div class="col-md-5">
        <div class="panel panel-warning">
          <div class="panel-heading">dc</div>
          <div class="panel-body">Universo DC. Creada en 1934, la editorial que ahora se llama DC Comics, fue adquirida por Warner Bros Entertainment en 1976, y desde entonces los superheroes DC multiplicaron su popularidad considerablemente. </div>
        </div>
      <div class="col-md-5">
        <div class="panel panel-danger">
          <div class="panel-heading">marvel</div>
          <div class="panel-body">de 1939 a 1952: Timely Comics
El joven Martin Goodman tenía una pequeña editorial de revistas pulp, llamada Western Fiction Publishing.​ Y al igual que muchos editores de pulps, orientó sus esfuerzos hacia el floreciente mercado de los cómic. Para ello, en 1939 creó la …
de 1952 a 1961: Atlas Comics
El fin de los súper no significó un gran revés para la empresa de Martin Goodman, ya que en 1950 publicaba más títulos que antes. Y además, sus obras las creaba una plantilla de artistas que trabajaban por un sueldo fijo. </div>
        </div>

      </div>
    </div>






<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
 
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
 
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
    <header>
      <h1>


      </h1>

   



  </form>
  </body>
</html>
</html>


Además llamo las librerías de Bootstrap en angular.json
 
 "styles": [
              "node_modules/bootstrap/dist/css/bootstrap.min.css",
              "src/styles.css"
            ],
            "scripts": [
              "node_modules/jquery/dist/jquery.min.js",
              "node_modules/@popperjs/core/dist/umd/popper.min.js",
              "node_modules/bootstrap/dist/js/bootstrap.min.js"
            ]

APP.COMPONENT.HTML

<router-outlet></router-outlet>
<button class="btn btn-danger">prueba boton</button>

INICIO SERVIDOR ng serve –open

