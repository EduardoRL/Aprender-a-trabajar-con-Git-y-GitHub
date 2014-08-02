Flujo de trabajo Git-GitHub
==================

Trozos de códigos con comentarios para aprender como se comunican.

### Flujo de trabajo con Git y GitHub:
1. Creo un repositorio con un README.md en GitHub.
2. Creo mi directorio de trabajo en local y le pongo el mismo nombre que el uitilizado en remoto.
3. Clonamos o descargamos el repositorio creado remoto a local con **git clone https://github.com/EduardoRL/NombreRepositorio.git**
  + Así lo descargarmos en nuestro PC pero éste solo será un carpeta con permisos de lecturas
4. configuro la cuenta (solo cuando se entra por primera vez):
  + **git config --global user.name "NombreUsuario"**
  + **git config --global user.email "CuentaCorreo"**
5. Inicializamos un repositorio en el directorio de trabajo en local con "**git init**" 
6. Creo un archivo en el directorio de trabajo con: **touch tuplas_listas_diccionarios.py**
7. Añado el archivo al **stage area** con: **git add tuplas_listas_diccionarios.py**
8. En cualquier momento podemos hacer: **git status** y nos dice el estado del repositorio
9. Asocio un comentario: **git commit -m "Este es un archivo de python vacío."**
10.  En PC hay un repositorio y remoto (GitHub) hay otro, vamos a conectarlos con: **git remote add origin https://github.com/EduardoRL/Aprendiendo-a-trabajar-con-Git-y-GitHub.git**
11. Trae todo lo que hay en remoto a mi PC con: **git pull origin master**
12. Envío todo mi códigos y archivos en mi PC (local) al remoto con: **git push origin master**
13. Ahora modifico en mi PC el archivo de python subido anteriormente al repositorio remoto.
14. Hago **git status** y me confirma que he modificado un archivo.
15. Lo añado al **stage area** con **git add -A**
16. Le asocio un comentario relacionado con esa modificación: **git commit -m "comentario"**
17. Antes de subir los cambios al remoto tengo que sincronizarlos con el remoto: **git pull origin master**
18. Vuevlo a subir los cambios al remoto con: **git push origin master** 
