# 🧁 Sistema de Ventas - Dulce Ruth

Este proyecto presenta una propuesta técnica de rediseño funcional para el módulo de facturación de **Dulce Ruth** (Insumos de Repostería). El objetivo principal fue transformar una interfaz administrativa saturada en una herramienta de venta ágil, visual y orientada a la eficiencia del usuario.

## 🎯 El Reto del Proyecto

El sistema original presentaba una alta carga cognitiva con campos técnicos innecesarios y falta de indicadores visuales críticos. El rediseño se enfocó en:

1. **Simplificar** la entrada de datos (UX).
2. **Visualizar** alertas críticas de Stock y Vencimiento en tiempo real.
3. **Automatizar** el cálculo de tarifas diferenciadas (Minorista/Mayorista).

## ✨ Características Principales

- **Interfaz Estilo Factura Real:** Utiliza una metáfora visual de "papel" para que el usuario se sienta familiarizado con el documento final.
- **Lógica de Tarifas Dinámica:** Permite alternar entre precios **Minorista** y **Mayorista**, recalculando automáticamente toda la tabla de productos agregados mediante JavaScript.
- **Gestión de Inventario Visual:**
  - Muestra el stock disponible directamente en el selector de productos.
  - Resalta productos con stock crítico o fechas de vencimiento próximas.
- **Cálculo Automatizado de Impuestos:** Gestión de Subtotal e IGV (18%) en tiempo real conforme se agregan o eliminan ítems.

## 🛠️ Stack Tecnológico

- **HTML5:** Estructura semántica del documento.
- **Tailwind CSS:** Framework utilizado para el diseño _Pixel Perfect_ y utilidades de estilo responsivo.
- **JavaScript (Vanilla ES6+):** Lógica de negocio pura para la gestión del carrito, manipulación del DOM y cálculos aritméticos.
- **Google Fonts (Inter):** Implementada para maximizar la legibilidad de datos numéricos y descripciones.

## 🚀 Instalación y Uso

El proyecto es totalmente autónomo y no requiere servidores complejos:

1.  Descargue el archivo `index.html`.
2.  Asegúrese de tener conexión a internet (para cargar Tailwind CSS vía CDN).
3.  Abra el archivo en cualquier navegador moderno (Chrome, Edge o Firefox).

## 🧠 Decisiones de UX/UI

- **Paleta de Colores:** Se utilizó un tono **Rosa (Pink-600)** para alinear la herramienta con la identidad de marca (repostería) y facilitar la identificación de botones de acción rápida.
- **Contraste de Totales:** Se aplicó un bloque oscuro (**Slate-900**) en la sección inferior para separar jerárquicamente los cálculos finales del área de edición de productos.
- **Microinteracciones:** Los botones de cambio de tarifa y el botón "+ AGREGAR" cuentan con estados de _hover_ y _active_ para proporcionar feedback inmediato al usuario.

---

**Entregado por:** Luis Pierre Oscco Lara - lpierre.dev@gmail.com
**Fecha de entrega:** 18 de Marzo, 2026
