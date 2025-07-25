# Manual Colaborativo: Uso de GitHub y el Control de Versiones

## Universidad: Universidad Valle del Momboy
## Carrera: Ingeniería de Computación
## Materia: Diplomado de Competencias Profesionales Para Ingenieros
## Docente: Prof. Gustavo Martínez y Prof. Edgardo Paolini
## Integrantes:
- Aaron Rosales
- Alexander Mendez


## Fecha:
Julio 2025

---

## Índice

1. Introducción  
2. ¿Qué es GitHub?  
3. Creación de un Repositorio  
4. Trabajo con Ramas y Pull Requests  
5. Issues y Gestión de Tareas  
6. Control de Versiones  
7. Buenas Prácticas en GitHub  
8. Conclusión  
9. Bibliografía  

---

## 1. Introducción

Este manual tiene como propósito ofrecer una guía básica y clara sobre el uso de GitHub y el control de versiones para proyectos colaborativos. Está orientado a estudiantes y personas que inician en el uso de herramientas de control de versiones, con un enfoque práctico y accesible.

GitHub es hoy una herramienta clave para desarrollar proyectos organizados, distribuidos y en equipo, permitiendo el seguimiento de cambios, control de versiones, revisión de código, y coordinación del trabajo mediante tareas.

---

## 2. ¿Qué es GitHub?

GitHub es una plataforma basada en la web que permite almacenar, gestionar y compartir proyectos de software usando el sistema de control de versiones Git.

Con GitHub, los equipos pueden:
- Colaborar en código de forma remota.
- Rastrear cambios a lo largo del tiempo.
- Proponer mejoras usando ramas y pull requests.
- Gestionar tareas con issues y tableros de proyectos.

---

## 3. Creación de un Repositorio

Para comenzar a usar GitHub, es necesario crear un repositorio. Los pasos básicos son:

1. Crear una cuenta en [github.com](https://github.com).
2. Hacer clic en "New Repository".
3. Asignar un nombre, una descripción y decidir si será público o privado.
4. Inicializarlo con un `README.md` si se desea.
5. Clonarlo en tu máquina local con el comando:
   ```bash
   git clone https://github.com/usuario/repositorio.git

---

# 4. Trabajo con Ramas y Pull Requests

Las ramas permiten desarrollar nuevas funcionalidades sin afectar el código principal.

### Pasos básicos:

**Crear una rama:**
```bash
git checkout -b nombre-rama
```

**Hacer cambios, luego guardar:**
```bash
git add .
git commit -m "Descripción del cambio"
git push origin nombre-rama
```

**Crear un Pull Request** desde GitHub para que tus compañeros revisen y aprueben los cambios antes de fusionar con la rama principal (`main` o `master`).

Los PR (*pull requests*) permiten hacer revisiones colaborativas con comentarios, sugerencias y aprobaciones antes de integrar los cambios.

---

# 5. Issues y Gestión de Tareas

Los *issues* permiten organizar y dividir el trabajo por tareas. Cada sección del manual puede ser una issue:

- **Issue 1:** Portada e Introducción
- **Issue 2:** ¿Qué es GitHub?
- **Issue 3:** Ramas y PRs
- **Issue 4:** Control de versiones
- **Issue 5:** Buenas prácticas en GitHub
- **Issue 6:** Diseño del README.md
- **Issue 7:** Estructura de carpetas y organización
- **Issue 8:** Versión final y conversión a PDF

Además, se puede usar el **Project Board** de tipo Kanban con columnas como:

- 📝 Por hacer  
- ⚙️ En progreso  
- ✅ Finalizado

Esto permite ver fácilmente el avance del equipo y distribuir responsabilidades.

---

# 6. Control de Versiones

Git controla el historial de cambios. Comandos básicos:

**Ver estado:**
```bash
git status
```

**Guardar cambios:**
```bash
git add archivo
git commit -m "Comentario"
```

**Ver historial:**
```bash
git log
```

**Crear etiquetas de versiones:**
```bash
git tag v1.0
git push origin v1.0
```

**Ver diferencias entre versiones:**
```bash
git diff
```

También se recomienda crear un archivo `CHANGELOG.md` para registrar los cambios por versión. Ejemplo:

```markdown
# CHANGELOG

## v1.0 - Versión inicial
- Se creó la estructura de carpetas
- Se agregaron las secciones principales del manual

## v1.1 - Revisión colaborativa
- Corrección de errores ortográficos
- Inclusión de imágenes y ejemplos
```

---

# 7. Buenas Prácticas en GitHub

- Usar nombres claros en commits y ramas.
- No trabajar directamente en `main`.
- Comentar y revisar los Pull Requests de otros miembros.
- Utilizar `.gitignore` para evitar subir archivos innecesarios.
- Etiquetar versiones estables.
- Mantener actualizada la documentación (`README.md`, `CHANGELOG.md`).
- Resolver conflictos con comunicación y revisión.

---

# 8. Conclusión

El uso de GitHub y Git permite trabajar de manera ordenada, colaborativa y segura. A través de esta guía básica, se puede comenzar a implementar flujos de trabajo que favorecen el desarrollo profesional en proyectos tecnológicos.

Controlar versiones no solo evita pérdidas de información, sino que también mejora la calidad del trabajo en equipo. GitHub no es solo para programadores: es una herramienta para cualquier proyecto colaborativo moderno.

---

# 9. Bibliografía

- GitHub Docs: https://docs.github.com  
- Pro Git Book: https://git-scm.com/book/en/v2  
- Atlassian Git Tutorials: https://www.atlassian.com/git/tutorials  
- Git Cheatsheet (PDF): https://education.github.com/git-cheat-sheet-education.pdf  
- GitHub Education: https://education.github.com