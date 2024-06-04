# Proyecto de API de Libros

## Modificaciones

### Manejo de Excepciones

- En primer lugar creé una clase `LibroException` para manejar los casos donde no se encuentra un libro.
- El método `getLibro` ahora envía un `LibroException` en el caso de que el libro no existe.
- También agregué un controlador global de excepciones para utilizaro manejar `LibroException` y retornar o devolver un estado HTTP 404 con un mensaje personalizado.

### Creación de Libros

- El método `postLibro` ahora retorna o devuelve el estado HTTP 201 (CREATED) al crear un nuevo libro.

### Estructura del Proyecto

- `libros.demo.com_tuuniversidad_exceptions`: Contiene las excepciones personalizadas.
- `libros.demo.com_tuuniversidad_repository`: Contiene la implementación del repositorio de libros.
- `libros.demo.com_tuuniversidad_controllers`: Contiene los controladores REST.

## Modificación del método getLibro

A continuación se muestra la ejecución respectiva:

![image](https://github.com/Cinthya-banchon/Modificar-Web-API-de-Libro/assets/170268641/aea3a6ab-447a-4df7-aa43-5f62c070c8dd)

## Controlador Global de Excepciones

A continuación se muestra la ejecución respectiva:

![image](https://github.com/Cinthya-banchon/Modificar-Web-API-de-Libro/assets/170268641/f46bf954-e128-4cc8-ab97-14b9cdfca836)

## Modificación del método postLibro

A continuación se muestra la ejecución respectiva:

![image](https://github.com/Cinthya-banchon/Modificar-Web-API-de-Libro/assets/170268641/50f5cc49-dc99-4a9f-b21f-47b496caed03)

Ahí se ha mostrado paso a paso. 
Así concluiría mi tarea.
