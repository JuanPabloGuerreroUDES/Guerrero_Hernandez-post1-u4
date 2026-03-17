# Galería Interactiva - U4

Aplicación web para gestionar tarjetas de contenido con categorización, filtrado y contador en tiempo real.

## Descripción

Galería Interactiva permite a los usuarios:

- Crear tarjetas con título, descripción y categoría
- Filtrar tarjetas por categoría (Tecnología, Ciencia, Arte)
- Eliminar tarjetas individuales
- Ver un contador en tiempo real de tarjetas visibles

## Instrucciones de Ejecución

### Requisitos
- Navegador web moderno
- No se requieren dependencias externas

### Pasos

1. **Abrir en navegador**
   - Opción A: Haz doble clic en `index.html`
   - Opción B: Usa un servidor local con Python: `python -m http.server 8000`

2. **Usar la aplicación**
   - Completa título, descripción y categoría
   - Haz clic en "Agregar Tarjeta"
   - Filtra por categoría con los botones
   - Observa el contador actualizar automáticamente
   - Haz clic en "Eliminar" para remover una tarjeta

## Tecnologías Utilizadas

- HTML5 - Estructura semántica
- CSS3 - Estilos responsive
- JavaScript Vanilla - Lógica de la aplicación (sin frameworks)

## Estructura de Archivos

```
Guerrero_Hernanez-post1-u4/
├── index.html       # Estructura HTML
├── app.js           # Lógica de la aplicación
├── styles.css       # Estilos
└── README.md        # Documentación
```

## Funcionalidades

- **Crear Tarjetas**: Valida campos, genera ID único y actualiza contador
- **Filtrar**: Muestra/oculta tarjetas según categoría seleccionada
- **Eliminar**: Elimina tarjetas del estado y del DOM
- **Contador**: Actualiza dinámicamente el número de tarjetas visibles

## Categorías

- Tecnología (Azul)
- Ciencia (Rojo)
- Arte (Naranja)

## Autor

Guerrero Hernández Juan Pablo - Post1 U4

Versión 1.0.0 - Marzo 2026
