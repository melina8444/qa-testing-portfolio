# Bug Report - Login Validation

## Título
El sistema no valida usuario vacío o con espacios

## Descripción
Al ingresar solo espacios en el campo usuario, el sistema muestra el mismo mensaje de error que cuando las credenciales son incorrectas.

## Pasos para reproducir
1. Ir a https://www.saucedemo.com/
2. En el campo usuario ingresar solo espacios
3. En el campo contraseña ingresar: secret_sauce
4. Presionar el botón Login

## Resultado actual
El sistema muestra el mensaje:  
Epic sadface: Username and password do not match any user in this service

## Resultado esperado
El sistema debería validar que el campo usuario no esté vacío o contenga solo espacios y mostrar un mensaje específico de validación.
