# 📝 Checklist de Control de Calidad (QC)

**Fecha de Revisión:** [DD/MM/AAAA]
**Revisor:** Mario Rosado
**Estatus Final:** [Aprobado / Requiere Cambios]

| No. | Requisito a Verificar | Criterio de Éxito | ¿Cumple? (Sí/No) | Observaciones/Hallazgos |
| :--- | :--- | :--- | :--- | :--- |
| **1. Estructura HTML Semántica** | Uso de etiquetas HTML5 | ¿Se usan `<header>`, `<nav>`, `<main>`, `<section>`, y `<footer>` correctamente? | **Sí** | Estructura principal sólida. |
| **2. Responsividad (ISO 25010 - Usabilidad)** | Diseño Adaptativo | ¿El layout se adapta y se ve bien en móvil (ej. menú vertical)? | **Sí** | Media Query en 600px funciona correctamente. |
| **3. Mantenibilidad (ISO 25010)** | Código CSS modular | ¿Se utilizan Variables CSS (`:root`) para la gestión de estilos principales? | **Sí** | Permite una modificación rápida y centralizada. |
| **4. Accesibilidad (WCAG/Contraste)** | Contraste de Color | ¿El color del texto es legible contra el fondo (ej. texto oscuro en fondo claro)? | **Sí** | `color-texto` (#212529) y `color-fondo` (#f8f9fa) tienen buen contraste. |
| **5. Eficiencia (ISO 25010)** | Optimización de Recursos | ¿El CSS está en un archivo externo y no en línea/incrustado? | **Sí** | Enlace correcto a `styles.css`. |
| **6. Navegación (Usabilidad)** | Enlaces Funcionando | ¿Todos los enlaces en `<nav>` y `<footer>` apuntan a la sección o destino correcto? | **Sí** | Usan `href="#id_seccion"`. |
