# Investigación: Comandos Básicos de Git y Flujo de Trabajo

---

## 🚀 Introducción

En el desarrollo de software moderno, el **control de versiones** es una herramienta fundamental. **Git** es un sistema de control de versiones distribuido diseñado por Linus Torvalds en 2005. A diferencia de los sistemas centralizados, Git permite que cada desarrollador tenga una copia completa del historial del repositorio en su máquina local.

El propósito de esta investigación es estructurar los comandos esenciales de Git que todo desarrollador debe dominar para gestionar proyectos, colaborar en equipo de forma ordenada y evitar conflictos en el código.

---

## Contenido

### 1. Configuración Inicial
Antes de registrar commits, es necesario identificar al autor de los cambios en el sistema:

```bash
# Definir el nombre de usuario global
git config --global user.name "Tu Nombre"

# Definir el correo electrónico global
git config --global user.email "tu@email.com"

# Verificar la configuración actual
git config --list

# Inicializar un nuevo repositorio en la carpeta actual
git init

# Clonar un repositorio existente desde un servidor remoto (GitHub, GitLab, etc.)
git clone <URL_DEL_REPOSITO>

# Consultar el estado del directorio de trabajo y del área de preparación
git status

# Añadir un archivo específico al área de preparación
git add archivo.txt

# Añadir todos los archivos modificados y nuevos al área de preparación
git add .

# Guardar los cambios del área de preparación en el historial del repositorio
git commit -m "feat: agregar la estructura base del proyecto"

# Ver el historial de confirmaciones (commits)
git log --oneline

# Listar las ramas locales
git branch

# Crear una nueva rama
git branch nombre-de-la-rama

# Cambiar a una rama existente
git switch nombre-de-la-rama

# Crear y cambiar a una nueva rama en un solo paso
git checkout -b nueva-rama

# Fusionar la rama especificada con la rama actual
git merge nombre-de-la-rama

# Eliminar una rama local que ya fue fusionada
git branch -d nombre-de-la-rama

# Vincular el repositorio local a un servidor remoto
git remote add origin <URL_DEL_REPOSITO>

# Descargar e integrar los cambios del repositorio remoto a la rama local
git pull origin main

# Obtener la información del remoto sin fusionar automáticamente
git fetch origin

# Enviar los commits locales a la rama remota
git push origin main

## 📌 Conclusión

El dominio de los comandos básicos de Git es un pilar fundamental para cualquier equipo de desarrollo de software. Comprender el ciclo de vida de los archivos (desde el directorio de trabajo local hasta el repositorio remoto) no solo reduce drásticamente el riesgo de pérdida de información y conflictos de código, sino que también garantiza un desarrollo ordenado y escalable.

Al integrar estas herramientas en la rutina diaria, los desarrolladores logran mantener un historial transparente y trazable, lo que facilita la auditoría de cambios y optimiza la colaboración en proyectos de cualquier escala.