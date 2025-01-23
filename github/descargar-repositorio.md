Andres Fernandez Buron  
Enero de 2025  
<hr>  

# Descargar un repositorio de GitHub  

- [Descargar un repositorio de GitHub](#descargar-un-repositorio-de-github)
  - [1. Descargar en formato ZIP](#1-descargar-en-formato-zip)
  - [2. Descomprimir en local](#2-descomprimir-en-local)
  - [3. Renombrar](#3-renombrar)

## 1. Descargar en formato ZIP

1. Con el navegador web, ir a la URL raíz del repositorio.  
   
    Por ejemplo:  
    ```https://github.com/andres123dev/my-seo-analyzer/```

2. En la zona superior derecha de la página web, hay un botón verde en el que pone ```Code```.  

3. Pinchar sobre él y en el desplegable seleccionar ```Download ZIP``` y esperar a que termine la descarga.  


## 2. Descomprimir en local

1. Abrir el explorador de archivos e ir a ```Descargas```.  

2. Hacer click derecho sobre el fichero ZIP y seleccionar ```Extraer todo``` y seguir el asistente.  

3. Cuándo termine de descomprimirse, entrar dentro de la carpeta.  


> [!NOTE] Esa carpeta contiene **una única carpeta que es la que contiene el repositorio en si**

## 3. Renombrar

El fichero ZIP descargado y la carpeta en la que se ha descomprimido el repositorio, <u>no tienen el nombre original</u> del repositorio.  

> [!CAUTION] Se le ha añadido un sujifo con el nombre de la rama  
> Por ejemplo el repositorio ```my-seo-analyzer```  se descarga cómo ```my-seo-analyzer-main```

<pre>
my-seo-analyzer-main      <b><- Carpeta descomprimida</b>
  |--> my-seo-analyzer-main
        |--> my_seo_analyzer
        |--> __main__.py
        |--> ...
</pre>

> [!TIP] Si es necesario, renombrar el directorio a su nombre original

  <pre>
    my-seo-analyzer-main
      |-> <b>my-seo-analyzer</b>     <b><- Renombrado</b>
          |-> my_seo_analyzer
          |-> __main__.py
          |-> ...
  </pre>

<br>
<br>
<hr>

[Volver arriba](#descargar-un-repositorio-de-github)  

[Volver al índice principal](../README.md)  
