# 🚀 Portal Web: Revista Tecnológica - Aseguramiento de la Calidad

**Integrantes:**
* Mario Rosado (Líder QA y Documentador QA)
* Luis Mario Bonilla (Desarrollador HTML)
* Enmanuel Bisonó (Diseñador CSS)

## 🎯 Propósito del Proyecto
El objetivo es diseñar y desarrollar un portal web para una revista tecnológica utilizando **HTML5** y **CSS3**, aplicando modelos de Aseguramiento de la Calidad (QA) definidos por el estándar **ISO/IEC 25010** y el marco de madurez **CMMI Nivel Inicial**.

## ⚙️ Metodología Aplicada
Hemos utilizado una aproximación **Ágil (Scrum)** en la ejecución del proyecto (dividido en sprints de planificación, desarrollo y QA) mientras referenciamos el modelo **CMMI** para la madurez del proceso.

### CMMI Nivel de Madurez: Inicial
* **Definición:** El proyecto opera en el Nivel Inicial, caracterizado por un proceso **impredecible** y a menudo **reactivo**.
* **Evidencia en el Proyecto:** Aunque se planificaron pasos, la implementación real se realiza sobre la marcha. El uso de la **Tabla de Trazabilidad** y la **Checklist QA** son los primeros pasos para movernos hacia un Nivel 2 (Gestionado), buscando formalizar y documentar nuestros procesos.

## ✅ Modelos y Estándares de Calidad

### 1. ISO/IEC 25010 (Calidad del Producto Software)
Nos hemos enfocado en tres características clave para garantizar la calidad del portal:

| Característica | Sub-Característica | Aplicación Práctica en el Código | Rol Responsable |
| :--- | :--- | :--- | :--- |
| **Usabilidad** | Reconocibilidad de la adecuación | Uso de etiquetas semánticas (`<header>`, `<nav>`, `<footer>`) para navegación intuitiva. | Luis Mario Bonilla |
| **Mantenibilidad** | Analizabilidad y Capacidad para ser modificado | Uso de **Variables CSS** en `:root` para centralizar la gestión de colores y fuentes. | Enmanuel Bisonó |
| **Eficiencia de Desempeño** | Comportamiento temporal | Uso de **CSS en archivo externo** (`styles.css`) para permitir la carga en paralelo. | Enmanuel Bisonó |

### 2. Control de Calidad (QC)
El **Control de Calidad** se realizó mediante un **Peer Review** (revisión entre pares) y la aplicación de una **Checklist QA** (ver archivo `QA/checklist-QA.md`) para verificar la conformidad con los requisitos.
