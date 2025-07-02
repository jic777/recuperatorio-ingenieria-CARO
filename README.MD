# Recuperatorio Ingeniería - CARO, JUAN IGNACIO

## Descripción
Este proyecto es un formulario web sencillo que solicita el nombre y la edad del usuario. Valida que el nombre tenga al menos 3 caracteres y que la edad sea un número válido mayor o igual a 0. Si la edad es mayor o igual a 18, muestra un mensaje de bienvenida personalizado; si no, muestra un mensaje de error.

## Requerimientos funcionales
1. Mostrar un formulario con campos de nombre y edad.
2. Validar que el nombre tenga al menos 3 caracteres.
3. Validar que la edad sea un número válido y mayor o igual a 0.
4. Mostrar mensaje de bienvenida si la edad es mayor o igual a 18.
5. Mostrar mensaje de error si la edad es menor a 18.

## Requerimientos no funcionales
1. El formulario debe ser responsivo y amigable para el usuario.
2. El código debe estar documentado y bien estructurado.
3. El proyecto debe poder ser ejecutado dentro de un contenedor Docker usando Nginx.


## Cómo ejecutar

### Ejecutar localmente

Abrir `src/index.html` con cualquier navegador web moderno.

### Ejecutar con Docker

Para construir la imagen Docker:

	docker build -t recuperatorio .

Para correr el contenedor:

	docker run -d -p 8080:80 recuperatorio

Luego, abrir en el navegador: http://localhost:8080