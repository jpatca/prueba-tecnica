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

Además llamo las librerías de Bootstrap en angular.json

APP.COMPONENT.HTML

<router-outlet></router-outlet>

<button class="btn btn-danger">prueba boton</button>

INICIO SERVIDOR ng serve –open

