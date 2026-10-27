# Pronosticar el éxito en la NFL

Proyecto del curso "Programar con criterio en la era de la IA".
Pregunta: ¿qué características de un jugador, conocidas en el draft,
permiten pronosticar su éxito profesional?

Autor/a: Sebastian Mendez

## Datos
- Archivo: nfl_data.csv del repositorio phcs971/nfl-draft-dataset
  (licencia MIT), leído desde una URL fijada a la versión 54730ea.
- Contenido: 4 tablas con differentes criterios de eliminacion, ademas de media y mediana para algunas
- Base de análisis: Jugadores de futbol americano profesionales o intentando entrar a profesional, 3197 jugadores
  
## Variables principales
- Éxito observado: La variable principal fue el criterio que se uso para eliminar jugadores
- Predictores: Entre mas pruebas completadas tuviera un jugador, mas probable es que pase los filtros

## Decisiones de limpieza
1. Al principio se eliminaron a todas las entradas que no tuvieran todas las pruebas completas para poder tener una base de datos completa
2. Luego se decidio solo eliminar entradas que tenian 2 o mas pruebas faltantes para no eliminar a jugadores que normalmente no hacen una de las pruebas
3. Finalmente se eliminaron a todas las entradas que no tenian todas las pruebas exeptuando el bench press para que no todos los quarterbacks fueran eliminados

## Carpetas
- sesion-1/ a sesion-5/: trabajos de cada sesión
