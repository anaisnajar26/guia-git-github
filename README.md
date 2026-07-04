# 🚀 Git & Gitflow en Análisis de Datos: Conceptos Básicos, Funcionamiento y Metodologías

Este repositorio contiene el material didáctico completo diseñado para introducir a estudiantes y profesionales en el **control de versiones profesional**. El enfoque está completamente adaptado al ecosistema de la analítica y la ciencia de datos, ayudando a transformar el caos habitual de versiones de archivos en un flujo de trabajo limpio, colaborativo y seguro.

Este proyecto docente fue reconocido gracias a su estructura interactiva, documentación paso a paso y aplicación práctica con entornos de desarrollo reales.

---

## 📖 Contenido y Estructura del Material

El material didáctico está diseñado como un flujo continuo que va desde la teoría fundamental hasta simulaciones prácticas en equipos de datos:

### ⚙️ 1. Fundamentos e Infraestructura de Git
* **El Problema del Caos:** Explicación del clásico error de acumular archivos duplicados en local (`modelo_FINAL.py`, `modelo_BUENO_ULTIMO.py`).
* **Arquitectura Interna:** Diferenciación práctica entre los tres estados clave de Git:
  * `Working Directory` (Carpeta local de edición).
  * `Staging Area` (Zona de preparación/selección de cambios).
  * `Repository` (Historial definitivo y permanente).

### 💻 2. Laboratorio Práctico & Demos por Entorno
El repositorio incluye demostraciones detalladas paso a paso sobre tres interfaces habituales en el sector:
* **La Terminal (CLI):** Uso de comandos esenciales nativos (`git init`, `git add`, `git status`, `git commit -m`).
* **PyCharm (IDE):** Integración del control de versiones visual dentro del entorno de desarrollo de Python (gestión de remotos, commits y empuje a la nube).
* **GitHub Desktop (GUI):** Gestión automatizada de repositorios mediante interfaz gráfica, control automático de cambios y sincronización bidireccional (`Push` / `Pull`).

### 🤝 3. Entorno Colaborativo y Metodología GitFlow
* **Flujo Profesional:** Uso de `git clone`, `git pull`, `git push` y la gestión de revisiones mediante **Pull Requests (PR)** para garantizar código funcional y limpio antes de integrar.
* **Modelo GitFlow:** Estructuración del desarrollo mediante ramas (*branches*) predefinidas y segregadas:
  * `main`: Código probado listo para producción.
  * `develop`: Integración diaria del trabajo del equipo.
  * `feature/`: Ramas temporales para tareas específicas (ej. reportes de modelos o ingeniería de variables).
  * `release/` y `hotfix/`: Ramas de pulido y solución de fallos urgentes.
* **Gestión de Conflictos:** Simulación realista de coordinación entre perfiles de *Data Scientist* y *Data Engineer* uniendo sus avances y solucionando solapamientos de código.



---

## 🎯 Conclusiones y Propósito del Proyecto
* **Competencia Esencial:** El control de versiones eficiente es un pilar obligatorio en la ingeniería y ciencia de datos para garantizar la reproducibilidad de los modelos.
* **Trabajo en Equipo:** La adopción de metodologías como GitFlow previene la pérdida de código y optimiza la integración de arquitecturas complejas de datos en entornos de producción.
* **Enfoque Didáctico:** Este material reduce la curva de aprendizaje técnico, facilitando una transición fluida desde entornos locales aislados hacia flujos de trabajo colaborativos y profesionales.



---
*Diseñado, estructurado y expuesto por: Anaís Nájar Martínez*
