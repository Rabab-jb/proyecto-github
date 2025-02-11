# proyecto-github

Este proyecto es una práctica de Git en la que se documentan todos los comandos y pasos realizados.

## Pasos realizados hasta ahora:

### 1. Crear el repositorio en GitHub
- Se creó un repositorio llamado `proyecto-github` en GitHub.

### 2. Clonar el repositorio en local
- Se clonó el repositorio con el comando:
git clone https://github.com/TU-USUARIO/proyecto-github.git

- Se accedió a la carpeta del repositorio:
cd proyecto-github

### 3. Crear `index.html` y `README.md`
- Se creó un archivo `index.html` y un archivo `README.md`.
- Se documentaron los pasos en `README.md`.

### 4. First Commit
- Se añadió el contenido inicial y se hizo el primer commit:
git add . git commit -m "Archivos iniciales" git push origin main


### 5. Modificar `index.html` agregando `<h1>`
- Se añadió el siguiente contenido en `index.html`:
<h1>Hola, este es mi proyecto</h1> ```

### 6.Commit "agregado titulo"
Se hizo un commit con el mensaje "agregado titulo":
git add index.html
git commit -m "agregado titulo"

### 7.Actualizar README.md con estos pasos
Se añadieron los pasos documentados en este archivo.
Se hizo un commit con el mensaje:
git add README.md
git commit -m "actualizado el readme.md"

### 8. Usar `git log` y guardar el hash del primer commit en `log_com.txt`
- Se ejecutó el comando: git log --oneline
- Se identificó el hash del primer commit y se guardó en `log_com.txt` con el formato:
Primer commit: HASH_DEL_PRIMER_COMMIT
- Se realizó un commit:
git add log_com.txt git commit -m "guardado hash del primer commit"

### 9. Crear la rama `estilos`
- Se creó una nueva rama llamada `estilos` con: git branch estilos
- Se cambió a la rama `estilos` con: git checkout estilos

### 10. En la rama `estilos`, añadir `styles.css` y darle estilos al título
- Se creó el archivo `styles.css` con los siguientes estilos:
h1 { color: blue; text-align: center; font-size: 2em; }
- Se guardó y se añadió al repositorio:
git add styles.css git commit -m "añadido styles.css con estilos para el título"


### 11. Modificar `index.html` para enlazar `styles.css`
- Se agregó la siguiente línea en `<head>` de `index.html`:

### 12. Commit "agregado css"
- Se realizó un commit con el mensaje: git add .
git commit -m "agregado css"

### 13. Fusionar estilos en main
- Se cambió a la rama main con el comando: git checkout main.
- Se fusionó la rama estilos en main: git merge estilos

## 14. Actualizar README.md con estos pasos
- Se añadieron los pasos realizados en este archivo.



