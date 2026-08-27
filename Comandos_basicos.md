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