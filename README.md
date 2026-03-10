# Calculadora de Utilidad ASAI

Una calculadora web profesional y responsiva para calcular márgenes de utilidad en Conexiones Americanas y comparar con precios sugeridos en ASAI.

## Características

- **Interfaz Limpia y Moderna**: Diseño minimalista corporativo con paleta azul profesional
- **Cálculos en Tiempo Real**: Los resultados se actualizan automáticamente mientras escribes
- **Comparativa ASAI**: Calcula automáticamente el 35% del costo y duplica el precio sugerido
- **Completamente Responsivo**: Funciona perfectamente en dispositivos móviles, tablets y desktop
- **Sin Dependencias**: HTML, CSS y JavaScript vanilla puro - no requiere instalación de paquetes
- **Accesible**: Diseño accesible con contraste adecuado y etiquetas semánticas

## Uso

### Opción 1: Abrir directamente en el navegador
Simplemente descarga el archivo `index.html` y ábrelo en tu navegador web favorito.

### Opción 2: Servir localmente
Si tienes Python instalado:
```bash
python -m http.server 8000
```
Luego abre `http://localhost:8000` en tu navegador.

Con Node.js:
```bash
npx http-server
```

### Opción 3: Desplegar en GitHub Pages
1. Crea un repositorio en GitHub
2. Sube el archivo `index.html`
3. Ve a Settings → Pages
4. Selecciona la rama `main` como fuente
5. Tu calculadora estará disponible en `https://tu-usuario.github.io/tu-repositorio`

## Cómo Funciona

### Conexiones Americanas
1. Ingresa el **Costo de Conexión Americana**
2. Ingresa el **Precio de Venta**
3. La calculadora muestra automáticamente el **Margen de Utilidad** en porcentaje

### Con ASAI
La sección ASAI calcula automáticamente:
- **Costo**: 35% del costo de la Conexión Americana
- **Precio de Venta Sugerido**: El doble del costo ASAI
- **Margen de Utilidad**: Porcentaje de ganancia basado en estos valores

## Ejemplo

```
Costo de Conexión Americana: 1500
Precio de Venta: 3000
Margen de Utilidad: 100%

Con ASAI:
Costo: 525 (35% de 1500)
Precio de Venta Sugerido: 1050 (525 × 2)
Margen de Utilidad: 100%
```

## Tecnología

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con variables CSS y media queries
- **JavaScript Vanilla**: Lógica de cálculos sin frameworks

## Compatibilidad

Funciona en todos los navegadores modernos:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## Personalización

Puedes personalizar fácilmente los colores editando las variables CSS en la sección `<style>`:

```css
:root {
    --primary: #0066cc;           /* Color principal */
    --foreground: #1a1a1a;        /* Color del texto */
    --background: #fafafa;        /* Color de fondo */
    /* ... más variables */
}
```

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## Autor

Creado con Manus AI - Marzo 2026

---

¿Preguntas o sugerencias? Abre un issue en el repositorio.
