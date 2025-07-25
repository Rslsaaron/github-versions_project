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

## Objetivo Principal del Documento

Este manual recopila buenas prácticas fundamentales para la realización de trabajos universitarios en grupo, con el fin de facilitar la organización, mejorar la productividad, y fomentar la colaboración efectiva entre los integrantes. A través de recomendaciones sencillas y aplicables, se abordan aspectos clave como la planificación, distribución de tareas, gestión del tiempo, uso adecuado de herramientas digitales, formatos académicos, normas de citación y la presentación final del trabajo.

* Fomentar la organización grupal efectiva, promoviendo roles y responsabilidades claras dentro del equipo.

* Establecer pautas para la planificación y gestión del tiempo, a fin de evitar improvisaciones y retrasos en la entrega.

* Unificar criterios sobre el formato y estilo del trabajo, incluyendo redacción, estructura, y presentación visual.

* Promover el uso correcto de normas de citación y referencias bibliográficas, garantizando la integridad académica.

* Sugerir herramientas tecnológicas útiles para la colaboración, edición conjunta y seguimiento del progreso.

* Orientar sobre la presentación oral o escrita del trabajo final, con consejos prácticos y recomendaciones visuales.

### Público al que va dirigido

Este manual está dirigido principalmente a estudiantes universitarios de cualquier carrera que necesiten desarrollar trabajos en equipo como parte de sus asignaturas. También puede ser útil para docentes que deseen orientar a sus estudiantes en metodologías colaborativas o para cualquier persona interesada en mejorar la organización y presentación de proyectos grupales.

### Metodología de trabajo colaborativo

El trabajo colaborativo se basa en la cooperación activa de todos los miembros del grupo, donde cada persona asume una función clara, participa en la toma de decisiones y contribuye con sus conocimientos y habilidades para alcanzar un objetivo común. Esta metodología se apoya en la comunicación constante, la planificación conjunta, el respeto por los tiempos y responsabilidades, y el uso de herramientas que permitan una organización efectiva del trabajo.

### Herramientas utilizadas para su elaboración

* GitHub: Plataforma que permite alojar, compartir y colaborar en proyectos. Aquí se publica el manual para que pueda ser consultado, editado o mejorado por otros usuarios.

* Git: Sistema de control de versiones que permite llevar un seguimiento de los cambios realizados en el proyecto, facilitando el trabajo en equipo sin perder información importante.

* Markdown: Lenguaje de marcado ligero utilizado para dar formato al contenido del manual (títulos, listas, enlaces, negritas, etc.), de forma sencilla y legible, tanto en editores de texto como en plataformas como GitHub.

---

## 2. ¿Qué es GitHub?

GitHub es una plataforma basada en la web que permite almacenar, gestionar y compartir proyectos de software usando el sistema de control de versiones Git.

Con GitHub, los equipos pueden:
- Colaborar en código de forma remota.
- Rastrear cambios a lo largo del tiempo.
- Proponer mejoras usando ramas y pull requests.
- Gestionar tareas con issues y tableros de proyectos.


# Herramientas digitales para el trabajo en equipo

El uso de herramientas digitales permite a los equipos de trabajo planificarse, compartir documentos, hacer seguimiento de tareas y comunicarse de forma efectiva. A continuación se describen algunas de las más recomendadas para proyectos universitarios o profesionales.

### Google Docs / Google Drive

Funcionalidades principales 

* Edición de documentos, hojas de cálculo y presentaciones en línea.

* Guardado automático y en la nube.

* Comentarios, sugerencias y chat en tiempo real.

* Control de versiones y historial de cambios.

* Almacenamiento compartido con carpetas organizadas.

**Ventajas**

* Gratuito y accesible desde cualquier navegador.
* Permite edición colaborativa simultánea.
* Integra otras herramientas como Google Meet, Calendar y Gmail.

**Desventajas**

* Requiere conexión a internet para trabajar en equipo.
* Limitado en funciones avanzadas de diseño o edición compleja.

**Ejemplo de uso académico**

Un grupo de estudiantes redacta su informe final en Google Docs, mientras cada miembro trabaja en una sección distinta. El profesor puede revisar el avance y dejar comentarios directamente sobre el documento.

### GitHub

Funcionalidades principales:

* Repositorios para almacenar archivos de código o documentación.

* Control de versiones con Git.

* Gestión de ramas, pull requests y revisiones.

* Wiki, Issues y gestión de tareas.

* Colaboración transparente y organizada entre múltiples usuarios.

**Ventajas**

* Ideal para trabajos técnicos y proyectos en equipo.
* Permite rastrear cada cambio y revertir errores.
* Compatible con Markdown, GitHub Pages y CI/CD.

**Desventajas**

* Curva de aprendizaje inicial si no se conoce Git.
* Menos visual que otras herramientas para gestión de tareas.

**Ejemplo de uso académico**

Un equipo de estudiantes de informática desarrolla un proyecto de software y documenta sus buenas prácticas en un repositorio GitHub. Cada miembro trabaja desde su PC y sincroniza su avance mediante Git.

###  Trello

Funcionalidades principales:

* Organización de tareas mediante tableros, listas y tarjetas.

* Etiquetas, fechas límite, listas de verificación y comentarios.

* Integración con Google Drive, Slack, etc.

* Visualización tipo Kanban para gestión ágil de tareas.

**Ventajas**

* Visual y fácil de usar.
* Excelente para planificar y dividir tareas.
* Gratuito con funciones útiles.

**Desventajas**

* Limitado en funciones analíticas o complejas.
* Puede volverse desorganizado si no se le da seguimiento.

**Ejemplo de uso académico**

Un equipo usa Trello para organizar su cronograma de entrega del trabajo final. Cada miembro se asigna tareas y se marca el avance en tiempo real.

### Notion

Funcionalidades principales:

* Espacios de trabajo que combinan notas, bases de datos, calendarios y documentos.

* Plantillas personalizables para gestión de proyectos.

* Colaboración en tiempo real y comentarios.

* Todo en un solo lugar: notas, archivos, tareas, enlaces, etc.

**Ventajas**

* Versátil, todo-en-uno y muy visual.
* Ideal para documentación, agenda y planificación.
* Sincronización en la nube, multiplataforma.

**Desventajas**

* Puede resultar abrumador al inicio por la cantidad de opciones.
* Algunas funciones avanzadas están en versión paga.

**Ejemplo de uso académico**

Un grupo utiliza Notion para estructurar su proyecto: redactan notas de investigación, enlazan referencias, organizan el cronograma y asignan responsabilidades por sección.

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