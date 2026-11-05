# UMarket — PMV 2.0

Prototipo académico de marketplace universitario, basado en las ocho capturas del PMV 1.0.

## Cuentas de prueba

- Comprador: `comprador@usil.pe` / `Demo1234`
- Vendedor: `vendedor@usil.pe` / `Demo1234`
- Código de verificación simulado: `123456`

El registro es solo una demostración: **no crea cuentas**. Los cambios y favoritos se guardan en `localStorage`, en el navegador actual.

## Funcionalidades

- Inicio y catálogo con búsqueda, filtros y ordenamiento.
- Detalle de publicación, favoritos, perfil de vendedor y reseñas ficticias.
- Inicio de sesión y registro en modales simulados.
- Panel de vendedor: publicar, editar, pausar, activar y eliminar.
- Vista previa de publicaciones y modal de confirmación.
- Botón de WhatsApp con mensaje contextual.
- Diseño adaptable a escritorio y móvil.

## Limitaciones importantes

- **No hay backend ni autenticación segura.** Nunca uses contraseñas reales.
- No hay pagos ni pedidos dentro de UMarket.
- Todos los perfiles, reseñas, insignias, ubicaciones y teléfonos son **datos de demostración**. El número de WhatsApp `51999999999` es un marcador ficticio.
- Los cambios no se sincronizan entre navegadores o dispositivos.
- Las imágenes cargadas se guardan en el navegador, con un límite de 1 MB; el almacenamiento disponible puede variar.

## Organización

- `index.html`, `catalogo.html`, `producto.html`, `vendedor.html`, `dashboard.html`, `publicar.html`: entradas de las seis páginas.
- `css/styles.css`: diseño global y responsive.
- `js/app.js`: lógica, roles, navegación, catálogo, publicaciones y modales (comentado por secciones).
- `data/`: datos iniciales JSON.
