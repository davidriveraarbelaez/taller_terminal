# Crear, mover, copiar y borrar archivos y carpetas

En la terminal, existen varios comandos que te permiten crear, mover, copiar y borrar archivos y carpetas. A continuación, se describen los comandos básicos para realizar estas operaciones.

## Crear archivos y carpetas
- `touch [nombre_archivo]`: Crea un archivo vacío con el nombre especificado.

  ```bash
  touch archivo.txt
  ```

- `mkdir [nombre_directorio]`: Crea un nuevo directorio con el nombre especificado.

  ```bash
  mkdir nueva_carpeta
  ```

## Mover y renombrar archivos y carpetas
- `mv [origen] [destino]`: Mueve o renombra un archivo o directorio.

  ```bash
  mv archivo.txt /ruta/al/nuevo/directorio/
  mv archivo.txt nuevo_nombre.txt
  ```

## Copiar archivos y carpetas
- `cp [origen] [destino]`: Copia un archivo o directorio.

  ```bash
  cp archivo.txt /ruta/al/nuevo/directorio/
  cp -r carpeta_original/ /ruta/al/nueva/copia/
  ```

## Borrar archivos y carpetas
- `rm [nombre_archivo]`: Elimina un archivo.

  ```bash
  rm archivo.txt
  ```

- `rmdir [nombre_directorio]`: Elimina un directorio vacío.

  ```bash
  rmdir carpeta_vacia
  ```

- `rm -r [nombre_directorio]`: Elimina un directorio y su contenido de forma recursiva.

  ```bash
  rm -r carpeta_con_contenido/
  ```

Con estos comandos, podrás gestionar archivos y carpetas desde la terminal de manera efectiva. Practica estos comandos para familiarizarte con ellos y mejorar tu eficiencia en el uso de la línea de comandos.