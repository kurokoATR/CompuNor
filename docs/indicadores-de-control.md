# Indicadores de control y estándares de desempeño

Son **estándares propuestos**. Se van a medir cuando haya una versión del sistema para probar; todavía no son resultados conseguidos.

Ciclo de control: 1) fijar el estándar, 2) medir, 3) comparar lo medido con el estándar, 4) corregir.

## A. Auditoría técnica del sistema

| Indicador | Cómo se mide | Estándar | Frecuencia | Si no se cumple |
|---|---|---|---|---|
| Capacidad de productos | Cantidad de productos cargados y consultables sin errores | 1.000 o más | En las pruebas | Revisar la forma de guardar los datos |
| Tiempo de búsqueda | Segundos entre pedir y ver los resultados | 3 s o menos | En las pruebas | Optimizar la consulta |
| Tiempo de registro de una venta | Minutos para cargar una venta completa | 1 minuto o menos | En las pruebas | Simplificar la pantalla |
| Coherencia del stock | Ventas confirmadas que descontaron stock / ventas confirmadas | 100 % | Cada semana | Corregir el error y recalcular el stock |
| Exactitud del inventario | Equipos cuyo stock coincide con el conteo físico / equipos contados | 98 % o más | Cada mes | Revisar los registros que no coinciden |

## B. Proceso de venta

| Indicador | Cómo se mide | Estándar | Frecuencia |
|---|---|---|---|
| Ventas registradas a tiempo | Ventas cargadas dentro de las 24 h / ventas totales | 100 % | Cada semana |
| Tasa de cancelación | Ventas canceladas / ventas registradas | 10 % o menos | Cada mes |
| Rotación de inventario | Unidades vendidas / stock promedio del período | Se define con los primeros datos reales | Cada mes |

## C. Proyecto y trabajo colaborativo

| Indicador | Cómo se mide | Estándar | Frecuencia |
|---|---|---|---|
| Cumplimiento del cronograma | Semanas reales / semanas planificadas (8) | 8 semanas o menos | Cada semana |
| Cambios que llegan a main por Pull Request | Cambios integrados por PR / cambios integrados | 100 % | Cada PR |
| Commits con mensaje descriptivo | Commits con prefijo y descripción clara / commits totales | 100 % | Cada PR |
| Historias de usuario con criterios de aceptación | Historias con criterios / historias totales | 100 % | Cada sprint |
