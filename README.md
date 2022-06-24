## Despliegue de apps Spring Boot en Heroku

Crear el archivo `system.properties` en la carpeta principal de projecto y agregar el comando:
``java.runtime.version=17``

1. Crear una cuenta en Heroku.com y github.com
2. Tener configurado git en tu ordenador
   1. 
       ``git config --global user.name "Avel40m"``
   2. ``git config --global user.email avel40m@gmail.com``
3. Subir el projecto a github desde Intellij IDEA desde la opción VSC > Share project in Github
4. Desde Heroku, crear app y elegir método Github y buscar el repositorio subido
5. Habilitar Deploy automatic y ejecutar Deploy