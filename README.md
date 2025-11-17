# Assets CDN

Repositorio centralizado de assets estáticos (imágenes, iconos, banners) para usar en múltiples proyectos.

## 🚀 Uso

Todos los assets están disponibles vía jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/[ruta-del-archivo]
```

### Ejemplos:

```html
<!-- Logo -->
<img src="https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/images/logos/logo.svg" alt="Logo">

<!-- Banner -->
<img src="https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/images/banners/hero-casino.jpg" alt="Banner">

<!-- Icono -->
<img src="https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/images/icons/check.svg" alt="Check">
```

### Con React/JSX:

```jsx
<img 
  src="https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/images/logos/logo.svg" 
  alt="Logo" 
/>
```

### Con CSS:

```css
.hero {
  background-image: url('https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/images/backgrounds/hero-bg.jpg');
}
```

## 📁 Estructura

```
assets-cdn/
├── images/
│   ├── logos/          # Logos de marcas y proyectos
│   ├── banners/        # Banners promocionales y hero images
│   ├── icons/          # Iconos SVG
│   ├── backgrounds/    # Fondos e imágenes decorativas
│   └── products/       # Imágenes de productos
├── fonts/              # Fuentes personalizadas
└── videos/             # Videos (usar con precaución, pueden ser pesados)
```

## ⚡ Ventajas

- **CDN Global**: Servidores rápidos en todo el mundo
- **Gratis**: Sin límites de ancho de banda
- **Cache automático**: Optimización de carga
- **Versionado**: Control con Git tags
- **Sin configuración**: Solo sube y usa

## 🔄 Versiones

Para usar una versión específica (recomendado en producción):

```html
<!-- Versión específica con tag -->
<img src="https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@v1.0.0/images/logos/logo.svg">

<!-- Última versión de main (desarrollo) -->
<img src="https://cdn.jsdelivr.net/gh/AlaStOrSC/BBassets@main/images/logos/logo.svg">
```

## 📝 Convenciones

- **Nombres de archivo**: kebab-case (logo-dark.svg, hero-banner.jpg)
- **Formatos recomendados**:
  - Logos e iconos: `.svg` (escalable)
  - Fotos: `.jpg` o `.webp`
  - Imágenes con transparencia: `.png` o `.webp`
- **Optimizar antes de subir**: Usa tinypng.com o similar

## 🚀 Proyectos que usan este CDN

- BombaCalor Landing
- Casino Promos
- Términos y Condiciones

---

**Última actualización**: Noviembre 2025
