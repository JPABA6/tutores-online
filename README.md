# Tutores Online — prototipo académico

**Integrantes:** JULIAN PABA y ROBERTO DE LOS REYES

## Incluye
- `index.html`: página de inicio.
- `tutores.html`: catálogo de tutores con filtros.
- `como-funciona.html`: explicación del proceso.
- `login.html` y `registro.html`: formularios de demostración.
- `css/styles.css`: estilos responsive.
- `js/app.js`: filtros y validación de demostración.
- `sql/schema.sql`: esquema MySQL relacional.
- `database-diagram.png`: diagrama de entidades y relaciones.

## Ejecutar localmente
Abre `index.html` en un navegador. Para probar mejor el proyecto, usa una extensión de servidor local o ejecuta `python -m http.server 8000` desde esta carpeta y abre `http://localhost:8000`.

## Publicar
1. Crea un repositorio en GitHub y sube todos los archivos de esta carpeta.
2. En GitHub abre **Settings → Pages**, selecciona la rama principal y la carpeta raíz, y guarda.
3. Espera a que GitHub Pages muestre la URL pública. El sitio puede navegar entre todas las páginas HTML.
4. Copia la URL real del repositorio y la URL real del hosting al informe PDF.

## Alcance y limitaciones
Este es un prototipo navegable de frontend. Los perfiles, tarifas y reseñas son ilustrativos. Los formularios validan datos en el navegador, pero no registran usuarios ni crean sesiones reales. El SQL es un diseño propuesto para una futura integración con backend y MySQL. No se deben presentar las funciones de autenticación, pagos o reservas como implementadas.
