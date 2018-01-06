# MANEJO DE FORMULARIOS

## Enlazando campos a un objeto del scope

1. Añadir un nombre al formulario y un metodo  a la directiva `ng-submit`

~~~
PRISTINE: Si no ha sido manipulado por el usuario de ninguna manera
~~~

- Una manera de manejar todos los datos de un formulario es creandole un objeto

2. Añadir lo siguiente a los inputs (entradas) :
    - `ng-model`
    - `name`
    - `required` (opcional)

3. Para quitar los mensajes de HTML5 por defector añadir al formulaario lo siguiente:
    - novalidate="novalidate"

4. Enviar como parametro a la funcion `guardar_datos` lo siguiente con la finalidad de saber si es valido o no la información:
    - formulario.$valid

- Tener en cuenta las clases de bootstrap `has-error` y `has-success`

5. Añadir la directiva `ng-class` al primer input `nombre`

6. Añadir validaciones en los inputs `nombre` e `email`

~~~
El problema es que hay mucha logica de validacion en la vista
~~~
