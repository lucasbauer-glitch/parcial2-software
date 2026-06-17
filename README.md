# 📝 Segundo Parcial - Ingeniería de Software
Este repositorio contiene el desarrollo del segundo parcial práctico de la materia. El objetivo principal es construir una estructura básica de software, documentarla correctamente y aplicar herramientas de contenedorización.

## Información del Estudiante
* **Nombre:** Lucas Alejandro Bauer
* **Fecha:** 17 de junio de 2026


##  Objetivos del Proyecto

El mini-proyecto cumple con los siguientes requisitos de la consigna:
* **Estructura Base:** Creación de un archivo `index.html` funcional.
* **Documentación:** Redacción y estructuración de este archivo `README.md`.
* **Dockerización:** Configuración y empaquetado del entorno utilizando Docker.
* **Control de Versiones:** Gestión del ciclo de vida del código sumando commits limpios y descriptivos en Git.


##  Tecnologías Utilizadas

* **HTML5** - Estructura de la página web.
* **Git** - Control de versiones.
* **Docker** - Containerización de la aplicación.

---

## 📦 Instrucciones de Ejecución (Próximamente)

> 💡 *Nota: Para levantar el contenedor de Docker una vez configurado el Dockerfile, podés usar los siguientes comandos:*

```bash
# Para construir la imagen
docker build -t parcial2-software .

# Para correr el contenedor
docker run -d -p 8080:80 parcial2-software