## Examen 1 <br> <br>
## Crear repositorio y carpeta para capturas <br>
![Imagen](IMAGENES/1.png)
## Agregar al repositorio y crear README <br>
![Imagen](IMAGENES/2.png)
## Commit inicial <br>
![Imagen](IMAGENES/3.png)
## Push inicial <br>
1. Para esto se debe escribir el comando "git push origin master" y ejecutarlo.
![Imagen](IMAGENES/PushInicial.png)
2. Ahora comprobaremos que el repositorio remoto si tenga los cambios.
![Imagen](IMAGENES/Comprobacion.png)
## Ignorar archivos <br>
1. Crear en el repositorio local un archivo llamado privado.txt.
2. Crear en el repositorio local una carpeta llamada privada. 
## Usando los siguientes comandos.
![Imagen](IMAGENES/Privado.png)
3. Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git. 
## Para esto crearemos el archivo .gitignore
![Imagen](IMAGENES/gitignore.png)
## Para esto escribiremos lo siguiente en el archivo .gitignore
![Imagen](IMAGENES/ignorar.png)
## Ahora veremos en el status para revisar que funciono
1. Aqui se puede ver que una vez modificado el archivo el unico que detecto fue el README
![Imagen](IMAGENES/Comprobar%20ignorar.png)
## Añadir Archivo 1.txt al repositorio local
![Imagen](IMAGENES/archivo1.png)
## Crear tag v0.1
1. Crear un Tag v0.1
2. Para esto se utiliza el siguiente comando. git tag -a v0.1 -m "tag v0.1"
3. Y se comprueba escribiendo git tag
![Imagen](IMAGENES/tagv0.1.png)
## Subir el tag <br>
1. Subir los cambios al repositorio remoto.
![Imagen](IMAGENES/agregado%20tag.png)
2. Podemos ir a gitgub para revisar que este agregado el tag.
![Imagen](IMAGENES/Comprobartag.png)
## Crear una rama v0.2
1. Crear una rama v0.2.
   ![Imagen](IMAGENES/crear%20rama.png)
2. Posiciona tu working directory en esta rama. 
   ![Imagen](IMAGENES/cabio%20de%20rama.png)
## Añadir Archivo 2.txt
1. Añadir un fichero 2.txt en la rama v0.2. 
![Imagen](IMAGENES/archivo%202.png)
## Crear una rama remota v0.2
1. Subir los cambios al repositorio remoto. 
## Hay que usar los siguientes comandos.
![Imagen](IMAGENES/Ramaremota.png)
## Comprobacion <br>
![Imagen](IMAGENES/ComprobacionRama.png)
## Merge Directo <br>
1. Posicionarse en la rama master. 
2. Hacer un merge de la rama v0.2 en la rama master. 
## Usaremos los siguientes comandos:
![Imagen](IMAGENES/merge.png)
## Tendremos un error pero es normal. <br>
## Merge con conflicto <br>
1. En la rama master poner "Hola" en el fichero Archivo1.txt y hacer commit usando los siguientes comandos. 
![Imagen](IMAGENES/Masterhola.png)
2. Posicionarse en la rama v0.2 y poner Adios en el archivo "Archivo1.txt" y hacer commit usando estos comandos. 
![Imagen](IMAGENES/Ramaadios.png)
3. Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2 , usar estos comandos:
![Imagen](IMAGENES/conflictoarreglado.png)
## Listado de Ramas <br>
1. Listar las ramas con merge y las ramas sin merge, usar estos comandos: 
![Imagen](IMAGENES/Listadoderamas.png)
## Arreglar conflicto <br>
1. Arreglar el conflicto anterior y hacer un commit. 
## En este paso deberia marcar un error pero como ya habia hecho antes un add y un commit este se arreglo.
![Imagen](IMAGENES/Arreglar%20conflicto.png)
1. Para arreglar el conflicto hay que hacer un add y un commit y debe aparecer lo siguiente.
![Imagen](IMAGENES/Resolver.png)
## Borrar rama <br>
1. Crear un tag v0.2 con este comando.
![Imagen](IMAGENES/Borrar%20rama%20tag.png)
2. Borrar la rama v0.2 con este comando: 
![Imagen](IMAGENES/Borrar%20rama%20tag.png)
## Listado de cambios <br>
1. Listar los distintos commits con sus ramas y sus tags. 
2. Acontinuacion se muestra el listado de cambios usando este comando: git log.
![Imagen](IMAGENES/Listacambios.png)

## EXamen Parte 2 <br> <br>

## Cuenta Gitbub
1. Poner una foto en tu perfil de GitHub. 
   ![Imagen](IMAGENES/Fotoperfil.png)
2. Poner el doble factor de autentificación en tu cuenta de GitHub. 
   ![Imagen](IMAGENES/Autenticar.png)
   ![Imagen](IMAGENES/Exito.png)
3. Añadir (si no lo has hecho aun) la clave pública (ssh) que se corresponde a tu equipo. 

## Uso social de github
1. Preguntar los nombres de usuario de GitHub de tus compañeros de clase, búscalos, y síguelos. 
   ![Imagen](IMAGENES/choi.png)
   ![Imagen](IMAGENES/jocelyn.png)
   ![Imagen](IMAGENES/gero.png)
   ![Imagen](IMAGENES/jose.png)
2. Seguir los repositorios RA del resto de tus compañeros. 
   
3. Añadir una estrella a los repositorios RA del resto de tus compañeros. 
 ![Imagen](IMAGENES/estrella%20choi.png)
 ![Imagen](IMAGENES/estrella%20gero.png)
 ![Imagen](IMAGENES/estrella%20joss.png)

## Crear una tabla <br>
| NOMBRE                        | GITHUB                                       |
| -------------                 | -------------                                | 
| AISLIN FERNANDA DIAZ AGUILAR  | https://github.com/diaz696                   |
| JOCELYN RODRIGUEZ PONCE       | https://github.com/JocelynRdzPon             |
| GERONIMO MARTINEZ DOMINGUEZ   |https://github.com/GeronimoMtz                |

## agregar colaborador
![Imagen](IMAGENES/colaborador.png)
## Organizacion <br>
![Imagen](IMAGENES/organizacion.png)
## crear equipo administradores <br>
![imagen](IMAGENES/Equipo.png)

 


   
