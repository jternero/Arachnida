# Arachnida






## *Spider*

 

Spider es un programa de Python que permite descargar imágenes de una página web de forma recursiva. El programa puede descargarse de forma local o desde una URL, y puede descargar imágenes de páginas vinculadas a la URL de forma recursiva.

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


Este código descargará imágenes de (https://www.example.com/)  y de todas las páginas vinculadas a ella hasta un nivel de 2. 
Las imágenes se guardarán en la carpeta  `./images`.



# *Scorpion*

Scorpion es una aplicación de Python que permite ver y editar los metadatos de imágenes. La aplicación utiliza la biblioteca PySimpleGUI para crear una interfaz gráfica de usuario (GUI) fácil de usar.

## Uso

Para utilizar la aplicación, sigue estos pasos:

1.  Abre el archivo  `scorpion.py`  en un editor de código o en la línea de comandos.
2.  Ejecuta el archivo  `scorpion.py`  para iniciar la aplicación.
3.  Haz clic en el botón "Image Folder" para seleccionar la carpeta que contiene las imágenes que deseas ver o editar.
4.  Selecciona una imagen de la lista de imágenes en la ventana de la izquierda.
5.  Los metadatos de la imagen se mostrarán en la ventana de la derecha. Si deseas editar los metadatos, haz clic en el botón "Edit Metadata".
6.  En la ventana de edición de metadatos, cambia los valores de los campos de metadatos según sea necesario.
7.  Haz clic en el botón "Save Changes" para guardar los cambios en los metadatos de la imagen.

## Requisitos

Scorpion requiere Python 3.x y las bibliotecas PySimpleGUI y Pillow. Para instalar estas bibliotecas, utiliza el siguiente comando:

```
pip install PySimpleGUI Pillow
```

## Limitaciones

    Scorpion sólo es capaz de leer y escribir los metadatos que se encuentran en el formato EXIF de las imágenes.
    
     No es capaz de leer o escribir metadatos en otros formatos como IPTC o XMP.

Además, se recomienda hacer una copia de seguridad de las imágenes antes de editar sus metadatos, ya que la edición de metadatos puede alterar la imagen original.



