# Proceso para crear repositorio remoto con GitHub
## Creación de un repositorio en GitHub
Ir a GitHub y crear una cuenta si no se tiene.  
Hacer click en New repository y configurar nombre, visibilidad y descripción.  
Copiar la URL del repositorio remoto.
### Vinculación del repositorio local con GitHub
Agregar el repositorio remoto: git remote add origin URL
#### Subir cambios al repositorio remoto
Subir la rama principal: git push   
Si hay cambios en el remoto que aún no se tienen localmente: git pull origin main  
Clonar un repositorio remoto: git clone URL