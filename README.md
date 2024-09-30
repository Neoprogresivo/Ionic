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

Para actualizar si es que no está la última versión, utilizar

npm install @ionic/angular@latest

Para crear una aplición con Ionic basta con:

ionic start nombreAplicacion tipo

Ejemplo:

ionic start ejemploApp blank

Para correr la aplicación

ionic serve

opcional se agrega -o para abrir en el navegador por defecto.

Comandos utilizados y sugerencias

----
# Generar APK

npm install (si deseas probar la aplicación ionic serve)

NOTA: Si hay alguna dependencia antigua, agregar --legacy-peer-deps

ionic build

npx cap add android

Si no está instalado:  npm install @capacitor/android

npx cap open android

Importación y descarga de archivos en android studio

Si hay instalado algun emulador Play, 

Sino descargar.

En el caso de error con la ruta del SDK, en este caso se resolvió actualizando Gradle (en AndroidStudio)
Y luego ya se puede generar el apk en la opción Build - Build Bundle(s)/APK(s) - Build APK(s)

El ejecutable queda en la carpeta android /app/build/outputs/apk/androidTest/debug

# En caso de error MODULE_NOT_FOUND

Limpiar el cache de NPM con

npm cache clean --force

Borrar todas las carpetas node_modules de la aplicación

Borrar el archivo package-lock.json de la aplicación

Instalar los paquetes nuevamente usando el comando npm install

Iniciar la aplicación utilizando ionic start
