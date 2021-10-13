# javacc-variables-correo-url-numeros
Este proyecto analiza un documento del tipo .txt y detecta las cadenas de texto que sean variables, números, correos y url's.

### verifica si tienes java instalado en tu pc escribiendo en el CMD java
Aqui se puede descargar https://www.oracle.com/java/technologies/downloads/#jdk17-windows

### Explicacion de como instalar javacc en Windows

1. Descargar la herramienta de javacc  https://bit.ly/39C5tGZ
2. Hay que descomprimir el archivo en el disco local C:
<br/><br/>
![](https://github.com/omar49511/javacc-variables-correo-url-numeros/blob/main/javacc%20programas/imagenes/Captura%20de%20pantalla%202021-10-12%20153039.png?raw=true)
<br/><br/>
3. Creas una carpeta en llamada target dentro de C:javacc-javacc-7.0.9
<br/><br/>
![](https://static.javatpoint.com/core/images/javacc6.png)
<br/><br/>
4. Descargar el archivo javacc-7.0.9.jar de https://bit.ly/3nKU3G4
5. Copiar el archivo .jar en la carpeta target creada
<br/><br/>
![](https://static.javatpoint.com/core/images/javacc7.png)
<br/><br/>
6. Renombrar el archivo como javacc.jar
<br/><br/>
![](https://static.javatpoint.com/core/images/javacc8.png)
<br/><br/>
7. Ir a variables de entorno
<br/><br/>
![](https://github.com/omar49511/javacc-variables-correo-url-numeros/blob/main/javacc%20programas/imagenes/Captura%20de%20pantalla%202021-10-12%20165954.png?raw=true)
![](https://github.com/omar49511/javacc-variables-correo-url-numeros/blob/main/javacc%20programas/imagenes/Captura%20de%20pantalla%202021-10-12%20170512.png?raw=true)
<br/><br/>
8. Buscar en variables del sistema la opcion de Path
<br/><br/>
![](https://github.com/omar49511/javacc-variables-correo-url-numeros/blob/main/javacc%20programas/imagenes/Captura%20de%20pantalla%202021-10-12%20170559.png?raw=true)
<br/><br/>
9. Darle en nuevo y agregar la ruta de la carpeta scripts
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137098134-359a72e3-c4e5-4a47-976a-56b62515477f.png)
<br/><br/>
10. Listo tienes javacc instalado en windows puedes verificar poniendo el comando javacc en el CMD
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137098564-e9985860-dc3b-4f29-8e92-bb5a30b7433a.png)
<br/><br/>
--
### Pasos para compilar el programa
1. Moverse a la ruta donde se guardo la carpeta javacc programas en mi caso el escritorio
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137099662-315c056b-ab73-4266-9722-49b83f265147.png)
<br/><br/>
2. Moverse a la ruta de la carpeta javacc programas
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137099845-838175cd-c529-4ea9-a18b-3a329d1f8806.png)
<br/><br/>
3. Ejecutar el comando javacc test.jj
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137100071-e6d87ae6-40d8-4922-b374-7863897e1173.png)
<br/><br/>
4. Si todo esta bien en la carpeta javacc programas se deberian crear esos archivos
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137100197-6b08ad20-404c-41a3-ac1c-f3f14ee31682.png)
<br/><br/>
5. Ahora compilamos los archivos .java con el comando javac \*.java
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137100751-dd30e307-aeee-415e-be9d-e69e93c8b154.png)
<br/><br/>
6. por ultimo escribimos el comando para que analice nuestro archivo .txt
<br/><br/>
![image](https://user-images.githubusercontent.com/72781778/137100915-b36c9b64-de8e-43c3-8cea-425b9bdb6bc4.png)



