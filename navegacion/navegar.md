# Navegación en la Terminal

La navegación en la terminal es una habilidad esencial para cualquier usuario de sistemas basados en Unix/Linux. A continuación, se presentan algunos comandos básicos para moverse por el sistema de archivos desde la línea de comandos.

## Comandos Básicos de Navegación
- `pwd`: Muestra el directorio de trabajo actual (Print Working Directory).
  
  ```bash
  pwd
  ```
- `ls`: Lista los archivos y directorios en el directorio actual.
  
  ```bash
  ls
  ```
- `cd [directorio]`: Cambia al directorio especificado. Si no se proporciona un directorio, cambia al directorio home del usuario.
    
```bash
cd /ruta/al/directorio
cd          # Cambia al directorio home
```

- `cd ..`: Sube un nivel en la jerarquía de directorios (al directorio padre).
    
    ```bash
    cd ..
    ```

- `cd -`: Cambie al directorio anterior en el que estaba.

    ```bash
    cd -
    ```

## Consejos Adicionales
- Use la tecla `Tab` para autocompletar nombres de archivos y directorios.
- Use `ls -l` para obtener una lista detallada de archivos y directorios.
- Use `ls -a` para ver archivos ocultos (aquellos que comienzan con un punto `.`).
- Combine opciones, por ejemplo, `ls -la` para ver una lista detallada que incluya archivos ocultos.
- Use `clear` para limpiar la pantalla de la terminal.

```bash
clear
```

Con estos comandos y consejos, podrás navegar eficazmente por el sistema de archivos desde la terminal. Practica estos comandos para familiarizarte con ellos y mejorar tu eficiencia en el uso de la línea de comandos.