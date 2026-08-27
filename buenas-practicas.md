#  Buenas Prácticas para Trabajar en GitHub

Aquí tienes toda la información organizada para que tus proyectos en equipo sean un éxito.

---

### 1.  Usar un repositorio bien organizado

El repositorio debe tener una estructura clara. Cada carpeta tiene que cumplir un propósito específico.

**Ejemplo de estructura ideal:**

```text
mi-proyecto/
├── README.md
├── src/
├── tests/
├── docs/
├── .gitignore
└── LICENSE
```
###  2. Crear un buen README

El archivo `README.md` es la carta de presentación de tu proyecto. 

**Un buen README debe explicar:**
* **Qué hace** el proyecto.
* **Cómo instalarlo** paso a paso.
* **Cómo ejecutarlo** en la computadora.
* **Qué tecnologías** utiliza.
* **Cómo contribuir** al código.
* **Ejemplos de uso** con imágenes o código.

---###  3. Hacer commits pequeños y descriptivos

Evita hacer un único commit gigante que diga `"trabajo terminado"`. Es mejor guardar los cambios en partes pequeñas.

**Ejemplos de buenos commits:**
* `Añade formulario de registro`
* `Corrige validación del correo`
* `Actualiza documentación de instalación`
* `Añade pruebas para usuarios`

---
###  4. Usar ramas (branches)

Si trabajan varias personas en el equipo, nunca hagan cambios directamente sobre la rama principal (`main`).

**Ejemplo de organización de ramas:**
*  `main`
  *  `feature/login`
  *  `feature/registro`
  *  `fix/validacion-email`

---
###  5. Revisar los Pull Requests

Antes de mezclar el código con `main`, otra persona del equipo debe revisar el trabajo.

**¿Qué se comprueba en la revisión?**
* Que el código funcione.
* Que no rompa otras partes del proyecto.
* Que siga las reglas del equipo.
* Que no incluya contraseñas o información sensible.
* Que todas las pruebas pasen con éxito.
