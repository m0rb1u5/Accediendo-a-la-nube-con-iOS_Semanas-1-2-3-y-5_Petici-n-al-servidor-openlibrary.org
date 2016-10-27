# Petición al servidor openlibrary.org
Tarea "Petición al servidor openlibrary.org" del curso "Accediendo a la nube con iOS" que se lleva en el portal Coursera.
## Instrucciones
En este entregable desarrollarás una aplicación usando Xcode que realice una petición a [Open Library](https://openlibrary.org/)

Para ello deberás crear una interfaz de usuario, usando la herramienta Storyboard que contenga:

1. Una caja de texto para capturar el ISBN del libro a buscar
2. EL botón de "enter" del teclado del dispositivo deberá ser del tipo de búsqueda ("Search")
3. El botón de limpiar ("clear") deberá estar siempre presente
4. Una vista texto (**Text View**) para mostrar el resultado de la petición

Un ejemplo de URL para acceder a un libro es:

[https://openlibrary.org/api/books?jscmd=data&format=json&bibkeys=ISBN:978-84-376-0494-7](https://openlibrary.org/api/books?jscmd=data&format=json&bibkeys=ISBN:978-84-376-0494-7)

Su programa deberá sustituir el último código de la URL anterior (en este caso 978-84-376-0494-7) por lo que se ponga en la caja de texto

Al momento de presionar buscar en el teclado, se deberá mostrar los datos crudos (sin procesar) producto de la consulta en la vista texto en concordancia con el ISBN que se ingreso en la caja de texto

En caso de error (problemas con Internet), se deberá mostrar una alerta indicando esta situación

Sube tu solución a GitHub e ingresa la URL en el campo correspondiente

## Criterios de revisión
1. ¿Existe una enlace a GitHub con el proyecto?
  - Si (1 punto)
  - No (0 puntos)
2. ¿El programa está hecho en Swift?
  - Si (1 punto)
  - No (0 puntos)
3. ¿Tiene un campo de texto que permite la captura del ISBN?
  - Si (1 punto)
  - No (0 puntos)
4. ¿Al hacer clic sobre el campo de texto, el teclado que emerge muestra la tecla de “Entrada” como “Búsqueda”?
  - Si (1 punto)
  - No (0 puntos)
5. La marca de "limpiar" en la caja de texto aparece todo el tiempo
  - Si (1 punto)
  - No (0 puntos)
6. En caso de falla en Internet, se muestra una alerta indicando ese problema
  - Si (1 punto)
  - No (0 puntos)
7. Se muestra el resultado en concordancia al ISBN ingresado
  - Si (5 puntos)
  - No (0 puntos)

## Resultado
Se muestra la pantalla del iPhone 7 al ejecutar el programa:
* Se muestran los datos crudos (sin procesar) producto de la consulta en la vista texto en concordancia con el ISBN que se ingreso en la caja de texto:

![Alt Text](https://github.com/m0rb1u5/Accediendo-a-la-nube-con-iOS_Semana-1_Petici-n-al-servidor-openlibrary.org/raw/master/out4_1.gif)

* <a name="resultado_error"></a> En caso de falla o de producirse algún error se muestra una alerta con el código y descripción del error:

![Alt Text](https://github.com/m0rb1u5/Accediendo-a-la-nube-con-iOS_Semana-1_Petici-n-al-servidor-openlibrary.org/raw/master/out4_2.gif)

***

# Procesando el resultado de la petición al servidor openlibrary.org
Tarea "Procesando el resultado de la petición al servidor openlibrary.org" del curso "Accediendo a la nube con iOS" que se lleva en el portal Coursera.
## Instrucciones
En este entregable desarrollarás una aplicación usando Xcode que después de haber realizado una petición a [Open Library](https://openlibrary.org/) (entregable anterior) analice os datos JSON obtenidos y los presente de manera adecuada

Para ello deberás crear una interfaz de usuario, usando la herramienta Storyboard que contenga:

1. Una caja de texto para capturar el ISBN del libro a buscar
2. EL botón de "enter" del teclado del dispositivo deberá ser del tipo de búsqueda ("Search")
3. El botón de limpiar ("clear") deberá estar siempre presente
4. En la vista deberás poner elementos para mostrar:
  - El título del libro
  - Los autores (recuerda que está en plural, pueden ser varios)
  - La portada del libro (en caso de que exista)

Un ejemplo de URL para acceder a un libro es:

[https://openlibrary.org/api/books?jscmd=data&format=json&bibkeys=ISBN:978-84-376-0494-7](https://openlibrary.org/api/books?jscmd=data&format=json&bibkeys=ISBN:978-84-376-0494-7)

Su programa deberá sustituir el último código de la URL anterior (en este caso 978-84-376-0494-7) por lo que se ponga en la caja de texto

Al momento de presionar buscar en el teclado, se deberá mostrar los datos crudos (sin procesar) producto de la consulta en la vista texto en concordancia con el ISBN que se ingreso en la caja de texto

En caso de error (problemas con Internet), se deberá mostrar una alerta indicando esta situación

Sube tu solución a GitHub e ingresa la URL en el campo correspondiente

## Criterios de revisión
La aplicación deberá tener la funcionalidad especificada y en la vista se deberán encontrar los siguientes elementos:

1. Una caja de texto para capturar el ISBN del libro a buscar
2. EL botón de "enter" del teclado del dispositivo deberá ser del tipo de búsqueda ("Search")
3. El botón de limpiar ("clear") deberá estar siempre presente
4. En la vista deberás poner elementos para mostrar:
  - El título del libro
  - Los autores (recuerda que está en plural, pueden ser varios)
  - La portada del libro (en caso de que exista)
5. En caso de error (problemas con Internet), se deberá mostrar una alerta indicando esta situación

## Resultado
Se muestra la pantalla del iPhone 7 al ejecutar el programa:
* A partir del ISBN tipeado se muestran los datos procesados que son la información del libro buscado. Estos son mostrados de manera adecuada y con atributos:

![Alt Text](https://github.com/m0rb1u5/Accediendo-a-la-nube-con-iOS_Semana-1_Petici-n-al-servidor-openlibrary.org/raw/master/out5.gif)

* En caso de falla o de producirse algún error se muestra una alerta con el código y descripción del error como se muestra en el resultado de [Petición al servidor openlibrary.org](#resultado_error)

***
Juan Carlos Carbajal Ipenza
