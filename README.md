# Arachnida
Web Scrapping Program




## *Spider*

 

Spider Gonzalez es un programa de Python que permite descargar imágenes de una página web de forma recursiva. El programa puede descargarse de forma local o desde una URL, y puede descargar imágenes de páginas vinculadas a la URL de forma recursiva.

## Uso

Para utilizar el programa, se pueden utilizar las siguientes opciones de línea de comandos:

-   `url`: URL de la página web que se analizará.
-   `-r`  o  `--recursive`: Descargar imágenes de páginas vinculadas a la URL de forma recursiva.
-   `-l`  o  `--level`: Nivel máximo de recursión al descargar imágenes.
-   `-p`  o  `--path`: Ruta de la carpeta donde se guardarán las imágenes descargadas.
-   `-c`  o  `--clean`: Eliminar la carpeta de imágenes antes de descargar.

Ejemplo de uso:


```
python spider.py -r -l 2 -p ./images https://www.example.com

```

**`Si no se pasa ningún parámetro, el programa le pedirá al usuario que introduzca los valores necesarios`**.

Este código descargará imágenes de (https://www.example.com/)  y de todas las páginas vinculadas a ella hasta un nivel de 2. Las imágenes se guardarán en la carpeta  `./images`.



