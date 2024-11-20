

**`README.md`**:

```markdown
# Comandos de Git Más Usados 📋

Esta es una referencia rápida de los comandos de Git que usamos frecuentemente en este proyecto. Úsala como guía para trabajar de manera eficiente.

---

## 📂 Configuración del Repositorio

### 1. Inicializar un repositorio:
```bash
git init
```

### 2. Agregar un remoto:
```bash
git remote add origin <url-del-repositorio>
```

### 3. Verificar los remotos configurados:
```bash
git remote -v
```

---

## 🛠️ Trabajo con Archivos

### 1. Agregar archivos al área de preparación (staging area):
- Para agregar un archivo específico:
  ```bash
  git add <archivo>
  ```
- Para agregar todos los archivos:
  ```bash
  git add .
  ```

### 2. Registrar un commit con un mensaje:
```bash
git commit -m "Mensaje claro del cambio realizado"
```

### 3. Verificar el estado del repositorio:
```bash
git status
```

---

## 🌿 Trabajo con Ramas

### 1. Crear una nueva rama:
```bash
git branch <nombre-de-la-rama>
```

### 2. Cambiar a otra rama:
```bash
git checkout <nombre-de-la-rama>
```

### 3. Crear una nueva rama y cambiar a ella al mismo tiempo:
```bash
git checkout -b <nombre-de-la-rama>
```

### 4. Listar todas las ramas (locales y remotas):
```bash
git branch -a
```

### 5. Eliminar una rama local:
```bash
git branch -d <nombre-de-la-rama>
```

---

## ⬆️ Subir Cambios

### 1. Subir la rama actual al remoto:
```bash
git push -u origin <nombre-de-la-rama>
```

### 2. Subir cambios después de un commit:
```bash
git push
```

---

## ⬇️ Descargar Cambios

### 1. Descargar cambios del remoto sin fusionarlos:
```bash
git fetch
```

### 2. Descargar y fusionar cambios automáticamente:
```bash
git pull
```

---

## 📜 Ver Historial de Cambios

### 1. Ver el historial de commits:
```bash
git log
```

### 2. Ver el historial de commits simplificado:
```bash
git log --oneline
```

### 3. Ver historial con un gráfico de ramas:
```bash
git log --all --oneline --graph
```

---

## 🔄 Flujos de Trabajo Comunes

### 1. Clonar un repositorio existente:
```bash
git clone <url-del-repositorio>
```

### 2. Crear un pull request (GitHub):
1. Sube los cambios con `git push`.
2. Ve al repositorio en GitHub.
3. Crea un **Pull Request** desde tu rama hacia `main`.

---

## 👥 Colaboración

### 1. Cambiar a la rama de un colaborador:
```bash
git checkout <nombre-de-la-rama>
```

### 2. Fusionar una rama en la actual:
```bash
git merge <nombre-de-la-rama>
```

---

## ❓ Resolver Problemas

### 1. Revertir cambios en un archivo antes de hacer commit:
```bash
git checkout -- <archivo>
```

### 2. Ver diferencias entre los archivos modificados:
```bash
git diff
```

### 3. Revertir el último commit (sin borrar los cambios):
```bash
git reset --soft HEAD~1
```

---
