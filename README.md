# Ionic
Para crear un proyecto en IONIC primero hay que verificar las versiones de los software que tenemos instalados, en el caso de que no exista una respuesta, puede set que no estén instalados.

Yo prefiero utilizar GitBash con Visual Studio Code y verificar

node --version

npm --version

ionic

Si no está instalado node, se debe instalar (personalemnte prefiero las versiones LTS)
https://nodejs.org/es

Para instalar IONIC

npm install -g @ionic/cli

Para crear una aplición con Ionic basta con:

ionic start nombreAplicacion tipo

Ejemplo:

ionic start ejemploApp blank

Para correr la aplicación

ionic serve

opcional se agrega -o para abrir en el navegador por defecto.
