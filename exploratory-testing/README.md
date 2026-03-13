# Exploratory Testing Notes

## Aplicación probada
https://www.saucedemo.com/

## Objetivo
Explorar el comportamiento del sistema de login.

## Pruebas realizadas

- Login con credenciales válidas
- Login con contraseña incorrecta
- Login con campo usuario vacío
- Login con usuario con espacios

## Observaciones

- El login funciona correctamente con credenciales válidas.
- El sistema muestra mensaje de error cuando las credenciales son incorrectas.
- Cuando el usuario contiene solo espacios, el sistema muestra el mismo mensaje de error que cuando las credenciales son incorrectas.

## Conclusión

El sistema permite identificar correctamente credenciales incorrectas, pero no diferencia entre usuario inválido y usuario vacío o con espacios.
