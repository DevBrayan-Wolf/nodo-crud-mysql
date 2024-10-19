# Cómo Funciona

## Rutas

La aplicación tiene las siguientes rutas definidas:

- `GET /` - Página de inicio.
- `GET /crear` - Vista para crear un nuevo estudiante.
- `POST /estudiantes` - Procesa la creación de un estudiante.
- `GET /listar` - Muestra la lista de estudiantes.

Estas rutas están gestionadas en el archivo `src/router.js`.

## Vistas

La aplicación utiliza EJS como motor de plantillas. Las vistas se encuentran en la carpeta `views` y están compuestas por:

- **inicio.ejs**: Página de inicio de la aplicación.
- **crear.ejs**: Formulario para crear un nuevo estudiante.
- **listar.ejs**: Tabla que muestra todos los estudiantes.

Cada vista está diseñada para ser sencilla y fácil de entender.

# Ejemplos de Uso

1. **Crear un Estudiante**:
   - Navega a `http://127.0.0.1:3600/crear`.
   - Completa el formulario con el nombre y email del estudiante.
   - Haz clic en "Crear Estudiante".

2. **Listar Estudiantes**:
   - Navega a `http://127.0.0.1:3600/listar` para ver todos los estudiantes registrados.
