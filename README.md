# 📸 Pixabay Image Search - Astro 🚀

Un buscador de imágenes utilizando la API de Pixabay, desarrollado con [Astro](https://astro.build/). Implementa filtrado de búsqueda, carga de imágenes con `Intersection Observer` para scroll infinito y lazy loading. Además, optimiza el rendimiento con técnicas como `debounce` y `throttle`.

## ✨ Características

- 🔍 **Búsqueda con filtros**: Encuentra imágenes con distintos criterios.
- ♾️ **Scroll infinito**: Carga más imágenes automáticamente al llegar al final de la página.
- 💤 **Lazy loading**: Mejora el rendimiento cargando imágenes solo cuando están cerca de la vista.
- ⚡ **Optimización con debounce y throttle**:  
  - `debounce` para evitar múltiples llamadas a la API en búsquedas rápidas.  
  - `throttle` para optimizar eventos de scroll y mejorar el rendimiento.
- 🚀 **Desarrollado con Astro**: Un framework moderno y rápido para la web.

## 📦 Instalación

1. Clona este repositorio:

   ```sh
   git clone https://github.com/lancer751/pixy-image-search
   cd pixy-image-search
   pnpm install
