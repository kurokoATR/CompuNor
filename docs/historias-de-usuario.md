# Historias de usuario - CompuNor

Formato: "Como [usuario], quiero [funcionalidad], para [beneficio]". Están cargadas como issues #1, #2 y #3 del repositorio y como tarjetas del tablero de GitHub Projects. Los criterios de aceptación se basan en el diccionario de datos de la Entrega N.º 3.

## HU-01

**Como** administrador, **quiero** registrar productos con nombre, categoría, marca, modelo, precio y cantidad disponible, **para** mantener actualizado el catálogo.

Criterios de aceptación:
- No se puede guardar un producto sin nombre, categoría, marca, modelo, precio y cantidad disponible.
- El precio no puede ser negativo.
- El producto registrado aparece en la búsqueda.
- El sistema permite registrar y consultar al menos 1.000 productos.
- Los resultados de una búsqueda aparecen en un máximo de 3 segundos en condiciones normales.

## HU-02

**Como** administrador, **quiero** consultar y modificar productos, **para** actualizar sus características y precios.

Criterios de aceptación:
- Se puede buscar un producto y ver todos sus datos.
- Los cambios de características y de precio se guardan y se ven al volver a consultar el producto.
- Las ventas ya registradas conservan el precio unitario con el que se vendieron.

## HU-03

**Como** vendedor, **quiero** registrar clientes con sus datos de contacto, **para** conservar la información de quienes compran.

Criterios de aceptación:
- Se guarda nombre completo, teléfono (como texto), localidad y medio de contacto.
- Un cliente registrado se puede consultar.
- Un cliente se puede asociar a una venta.

## Estado en el tablero (GitHub Projects)

| ID | Estado |
|---|---|
| HU-01 | En Progreso |
| HU-02 | Por Hacer |
| HU-03 | Por Hacer |

Columna Listo: diagrama BPMN del proceso de venta y diccionario de datos.

El tablero tiene además otras historias (HU-04 en adelante) que forman el resto del backlog.
