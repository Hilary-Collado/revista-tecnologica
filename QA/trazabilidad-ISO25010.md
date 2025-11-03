# 📋 Tabla de Trazabilidad ISO/IEC 25010

Este documento asegura que los requisitos de calidad definidos por el estándar ISO/IEC 25010 se cumplen a través de prácticas concretas en el portal web.

| ID Requisito QA | Característica ISO/IEC 25010 | Descripción del Requisito | Archivo/Línea de Código | Estatus |
| :--- | :--- | :--- | :--- | :--- |
| **QA-USR-001** | **Usabilidad** | La navegación principal (`<nav>`) debe ser visible y clara en todos los dispositivos. | `index.html` (Línea 23) y `styles.css` (Línea 46) | **Completado** |
| **QA-MNT-002** | **Mantenibilidad** | Todos los colores de la interfaz deben definirse mediante Variables CSS para facilitar cambios futuros. | `styles.css` (Línea 3-10) | **Completado** |
| **QA-MNT-003** | **Mantenibilidad** | El código debe usar comentarios para describir bloques clave (header, nav, footer). | `index.html` (Múltiples líneas) | **Completado** |
| **QA-PFR-004** | **Eficiencia de Desempeño** | El archivo CSS debe ser externo al HTML para mejorar el tiempo de carga. | `index.html` (Línea 9) | **Completado** |
| **QA-ACS-005** | **Accesibilidad** | Debe existir un contraste de color legible entre el texto y el fondo (según WCAG). | `styles.css` (Líneas 3-10, asegurando `color-texto` y `color-fondo`) | **Completado** |
