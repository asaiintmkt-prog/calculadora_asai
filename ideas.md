# Estrategia de Diseño - Calculadora de Utilidad ASAI

## Enfoque Seleccionado: **Minimalismo Corporativo Moderno**

He elegido un enfoque de **Minimalismo Corporativo Moderno** que combina elegancia profesional con funcionalidad clara. Este estilo es ideal para herramientas de cálculo financiero porque prioriza la legibilidad, la precisión visual y la confianza del usuario.

### Principios Centrales

1. **Claridad Funcional**: La interfaz debe comunicar exactamente qué hace sin distracciones visuales innecesarias.
2. **Jerarquía Visual Inteligente**: Los resultados más importantes (márgenes de utilidad) deben destacar naturalmente sin gritar.
3. **Confianza a través del Espacio**: El uso generoso de espacios en blanco transmite profesionalismo y control.
4. **Accesibilidad Prioritaria**: Contraste de colores cuidadoso y tipografía legible para usuarios de todas las edades.

### Filosofía de Colores

- **Paleta Principal**: Azul profesional (`#0066CC`) como color primario, con tonos neutros (grises cálidos).
- **Razonamiento**: El azul evoca confianza y profesionalismo en contextos financieros. Los grises cálidos crean calidez sin sacrificar la seriedad.
- **Intención Emocional**: Transmitir competencia, transparencia y control sobre los números.

### Paradigma de Diseño

- **Estructura Asimétrica Vertical**: Entrada → Cálculo Principal → Comparativa ASAI (flujo natural de lectura).
- **Tarjetas Flotantes**: Cada sección (Conexión Americana, ASAI) en su propia tarjeta con sombra suave para crear profundidad.
- **Ancho Contenido**: Máximo 500px para mantener el foco en los números sin abrumar.

### Elementos Distintivos

1. **Indicador Visual de Cambio**: Cuando el usuario ingresa valores, un pequeño indicador anima para mostrar que el cálculo se actualizó.
2. **Comparativa Lado a Lado (Móvil Adaptable)**: En desktop, ASAI aparece como una tarjeta complementaria; en móvil, se apila naturalmente.
3. **Tipografía Contrastante**: Títulos en peso 700 (bold), cuerpo en peso 400 para crear ritmo visual.

### Filosofía de Interacción

- **Retroalimentación Inmediata**: Los valores se actualizan sin necesidad de botones; el usuario siente control.
- **Transiciones Suaves**: Los números cambian con una animación de fade suave (200ms) para evitar saltos abruptos.
- **Estados Claros**: Campos vacíos muestran placeholders descriptivos; campos con valores tienen un borde sutil azul.

### Directrices de Animación

- **Entrada de Página**: Fade-in suave de 400ms para las tarjetas principales.
- **Cambio de Valores**: Transición de números con opacidad (200ms) para suavidad.
- **Hover en Inputs**: Cambio de borde a azul primario con transición de 150ms.
- **Resultado Destacado**: Cuando el margen de utilidad se calcula, un breve highlight (pulse suave) atrae la atención.

### Sistema Tipográfico

- **Fuente Display**: `Poppins` (bold, 700) para títulos y etiquetas principales.
- **Fuente Cuerpo**: `Inter` (400-500) para valores, placeholders y texto descriptivo.
- **Escala**: Títulos 24px, etiquetas 14px, valores 18px (peso 600).
- **Filosofía**: Poppins aporta modernidad y carácter; Inter asegura legibilidad en números.

---

## Decisiones de Implementación

- **Tema**: Claro (light mode) como predeterminado, con opción de oscuro en futuras iteraciones.
- **Componentes**: Tarjetas con sombra suave (`shadow-sm`), inputs con borde sutil, sin bordes redondeados excesivos (radio: 8px).
- **Espaciado**: Padding consistente de 24px en tarjetas, 16px entre elementos.
- **Contraste**: Texto oscuro (#1A1A1A) sobre fondo blanco, azul primario para acentos interactivos.
