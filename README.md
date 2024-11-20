# Comandos de Git Más Usados 📋

Esta es una referencia rápida de los comandos de Git que usamos frecuentemente en este proyecto. Úsala como guía para trabajar de manera eficiente.

---

## 📂 Configuración del Repositorio

### Inicializar un repositorio:
```bash
git init
Agregar un remoto:
bash
Copiar código
git remote add origin <url-del-repositorio>
Verificar los remotos configurados:
bash
Copiar código
git remote -v
🛠️ Trabajo con Archivos
Agregar archivos al área de preparación (staging area):
bash
Copiar código
git add <archivo>
Para agregar todos los archivos:
bash
Copiar código
git add .
Registrar un commit con un mensaje:
bash
Copiar código
git commit -m "Mensaje claro del cambio realizado"
Verificar el estado del repositorio:
bash
Copiar código
git status
🌿 Trabajo con Ramas
Crear una nueva rama:
bash
Copiar código
git branch <nombre-de-la-rama>
Cambiar a otra rama:
bash
Copiar código
git checkout <nombre-de-la-rama>
Crear una nueva rama y cambiar a ella al mismo tiempo:
bash
Copiar código
git checkout -b <nombre-de-la-rama>
Listar todas las ramas (locales y remotas):
bash
Copiar código
git branch -a
Eliminar una rama local:
bash
Copiar código
git branch -d <nombre-de-la-rama>
⬆️ Subir Cambios
Subir la rama actual al remoto:
bash
Copiar código
git push -u origin <nombre-de-la-rama>
Subir cambios después de un commit:
bash
Copiar código
git push
⬇️ Descargar Cambios
Descargar cambios del remoto sin fusionarlos:
bash
Copiar código
git fetch
Descargar y fusionar cambios automáticamente:
bash
Copiar código
git pull
📜 Ver Historial de Cambios
Ver el historial de commits:
bash
Copiar código
git log
Ver el historial de commits simplificado:
bash
Copiar código
git log --oneline
Ver historial con un gráfico de ramas:
bash
Copiar código
git log --all --oneline --graph
🔄 Flujos de Trabajo Comunes
Clonar un repositorio existente:
bash
Copiar código
git clone <url-del-repositorio>
Crear un pull request (GitHub):
Sube los cambios con git push.
Ve al repositorio en GitHub.
Crea un Pull Request desde tu rama hacia main.
👥 Colaboración
Cambiar a la rama de un colaborador:
bash
Copiar código
git checkout <nombre-de-la-rama>
Fusionar una rama en la actual:
bash
Copiar código
git merge <nombre-de-la-rama>
❓ Resolver Problemas
Revertir cambios en un archivo antes de hacer commit:
bash
Copiar código
git checkout -- <archivo>
Ver diferencias entre los archivos modificados:
bash
Copiar código
git diff
Revertir el último commit (sin borrar los cambios):
bash
Copiar código
git reset --soft HEAD~1