
## Despliegue de apps Spring Boot en Heroku (al final no pudo ser)

Crear archivo 'system.properties' en el proyecto con el contenido:

'''
java.runtime.version=23
'''

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
   1. 'git config --global user.name "AlbertoIS-GIT"'
   2. 'git config --global user.email correo@example.com'
3. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy auténtico y ejecutar el Deploy