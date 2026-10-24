
- **Alumno:** Alvaro Garcia
- **Bloque:**  00.01.8 Fase 0.8 Practicas
- **Fase / ejercicio:** Fase 0.8
- **Fecha de inicio:** 23/10/202
- **Fecha de entrega:** 24/10/2026

---

## 🎯 Qué se pedía

Una web que una empresa necesita mantener

## ⌨️ Comandos y pasos importantes

git status 
git add ruta
git diff
git diff --cached 
git init
git branch 
git remote add
git remote -v
git log
git log --oneline
git add .
git commit -m
git push
git check-ignore
git switch --detach

## 🛠️ Qué he hecho

He creado webs para una empresa
## 🚩 Qué me ha fallado y cómo lo he resuelto

Me lie con los comando al principio, pero despues lei bien y lo puse bien

## 🤔 Respuestas a las preguntas

1. Porque `01_Proyecto` contiene los archivos de la web que queremos controlar con Git, sin incluir el resto de carpetas y notas de la bóveda.

  2: Antes de `git add`, los archivos aparecían como no rastreados. Después de `add`, estaban preparados para el commit. Después de `commit`, los cambios quedaron guardados en el historial y el repositorio quedó limpio.

3. Porque necesitaba un repositorio propio en GitHub para guardar una copia remota del proyecto y compartirlo. `git remote add origin` conecta el repositorio local con el remoto.

4. Porque `git status` detecta archivos nuevos, mientras que `git diff -- web/index.html` muestra cambios no preparados en archivos que Git ya controla.

5. Comprobando que los vídeos existen en la carpeta y que están excluidos mediante `.gitignore`. Los comandos `git status --ignored` y `git check-ignore -v` permiten verificarlo.

6. Muestra un resumen de los cuatro archivos preparados, indicando las líneas añadidas y eliminadas. Las cifras dependen del contenido de los archivos.

7. Al visitar el primer commit, recuperamos la versión inicial del proyecto. Al volver a `main`, recuperamos la versión correspondiente al último commit de esa rama.

8. Porque el historial permite recuperar versiones anteriores, detectar errores y conocer los cambios realizados. GitHub facilitaría compartir el proyecto, trabajar en ramas, revisar cambios y colaborar con otros técnicos.

9. Si corrijo una errata en normas.html, repito `git status`, `git diff`, `git add`, `git diff --cached`, `git commit` y `git push`. No repito `git init` ni `git remote add origin`, porque ya están configurados

## 🔗 Enlaces

- **Vídeo de esta fase:** https://youtu.be/lR3XdMaWm1Q?si=YxXPSQaCuK2q59rG
- **Playlist:** https://www.youtube.com/playlist?list=PLLgILzwL5vvc

## 💭 Dudas / a repasar

Me ha quedado todo claro