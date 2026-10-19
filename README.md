# Proyecto: Desarrollo de Aplicaciones I

## A. Explicación de la Metodología de Desarrollo en V
Esta aplicación web se desarrolla siguiendo como guía la metodología en V, estructurando las fases descendentes de verificación y diseño técnico antes de la codificación.

### A.1- Contenido de la Rama Descendente (Fase de Verificación)

* **Análisis de Requisitos (Requirement Gathering):** 
  * Se definieron las necesidades de un sistema web dinámico con control de acceso basado en roles.
  * Funcionalidades principales: Panel principal dinámico, autenticación segura y segmentación de contenidos para Administrador, Gestor, Usuario Registrado y Visitante.

* **Análisis del Sistema (System Analysis):** 
  * Se especificó el comportamiento general del software bajo la arquitectura MVT (Modelo-Vista-Template) de Django.
  * Se determinó el uso de SQLite para la administración de usuarios y permisos.

* **Diseño de Software / Arquitectura (Software Design):** 
  * Stack tecnológico: Python, Django, HTML5 y CSS3 adaptativo con badges de color por rol.
  * Estructura modular: `core` para configuraciones globales y `webapp` para las vistas y plantillas.

* **Diseño de Módulos (Module Design):** 
  * Lógica interna de control de acceso basada en los atributos nativos de Django (`is_superuser`, `is_staff`, `is_authenticated`).
  * Renderizado condicional en la plantilla `home.html` para distintivos visuales (Rojo: Admin, Naranja: Gestor, Azul: Usuario, Gris: Visitante).

* **Punto de Inflexión:**
  * Transición de la especificación técnica a la preparación del entorno de desarrollo virtual y dependencias del framework.

* **Codificación (Coding):** 
  * Desarrollo del código fuente en Python, enrutamientos en `urls.py`, vistas en `views.py` e interfaz visual en plantillas Jinja/HTML.