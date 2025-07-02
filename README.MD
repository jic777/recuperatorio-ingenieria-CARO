- Recuperatorio Ingeniería - CARO, JUAN IGNACIO

-- Descripción

Formulario HTML que solicita nombre y edad, valida que sea mayor de 18 y muestra un mensaje de bienvenida.

-- Requerimientos funcionales

1. Mostrar formulario con nombre y edad.
2. Validar edad mayor o igual a 18.
3. Mostrar mensaje de bienvenida con el nombre.

-- Requerimientos no funcionales

1. Código comentado y ordenado.
2. App debe ser servida en contenedor Docker.

-- Ejecución

Para correr el proyecto:

docker build -t recuperatorio .

docker run -d -p 8080:80 recuperatorio

Luego abrir http://localhost:8080
