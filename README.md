# Mapa de Conflictos Laborales

Recreación de una página web interactiva que muestra un mapa de conflictos laborales en Argentina.

## Características

- **Mapa interactivo**: Utiliza Leaflet.js para mostrar ubicaciones de conflictos
- **Panel de estadísticas**: Muestra diferentes categorías de conflictos con barras animadas
- **Panel de noticias**: Sección lateral con últimas noticias relacionadas
- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla
- **Tema oscuro**: Diseño moderno con colores oscuros y acentos rojos

## Tecnologías utilizadas

- HTML5
- CSS3 (con gradientes y animaciones)
- JavaScript (Vanilla)
- Leaflet.js (biblioteca de mapas)
- CartoDB (tiles de mapa oscuro)

## Cómo usar

1. Abre el archivo `index.html` en tu navegador
2. Interactúa con el mapa haciendo zoom y moviendo la vista
3. Haz clic en los marcadores rojos para ver detalles de cada conflicto
4. Explora las estadísticas en el panel izquierdo
5. Revisa las noticias en el panel derecho

## Estructura del proyecto

```
MapaAgua/
│
├── index.html      # Estructura HTML principal
├── styles.css      # Estilos y diseño
├── script.js       # Lógica del mapa e interactividad
└── README.md       # Este archivo
```

## Personalización

- Modifica el array `conflictos` en `script.js` para agregar/editar ubicaciones
- Ajusta los colores en `styles.css` (busca `#dc143c` para el color rojo principal)
- Cambia las estadísticas en `index.html` dentro de la sección `.stats`

## Notas

- Los datos de conflictos son ilustrativos
- Las imágenes de noticias usan placeholders
- Requiere conexión a internet para cargar Leaflet.js y los tiles del mapa