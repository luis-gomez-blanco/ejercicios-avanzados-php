# EJERCICIOS AVANZADOS DE PHP

1. Mejora el ejercicio de conversión de divisas propuesto en *Ejercicios básicos* mediante una página que muestre 4 divisas diferentes en dos desplegables y un campo numérico. Será obligatorio para enviar el formulario que el campo numérico tenga algún valor numérico. La página del resultado muestra la conversión del campo numérico de la primera divisa a la segunda. Se deben emplear los controles HTML adecuados en cada caso, pudiendo validar la entrada mediante código JavaScript, que deberá ir en un archivo externo.

  *Bonus: Amplía el ejercicio con la posibilidad de introducir varias cantidades de diferentes divisas y poder convertir todas a otra.*

2. Crear un programa que, implementando distintos estilos que provienen de un archivo externo CSS, permita elegir mediante dos desplegables el color de fondo de la página y el color de la fuente. Se incluirán también dos casillas de selección donde indicar la decoración, negrita y/o cursiva, de la tipografía. Al enviar el formulario se cargará la misma página, aplicando los cambios de estilo. Las opciones seleccionadas por el usuario deben mantenerse en el formulario tras la carga de la página.

   *Bonus: 

4. Escribr un programa que permita al usuario introducir las temperaturas máximas y mínimas de las ciudades de Madrid, Barcelona, Sevilla y Bilbao (por ese orden) para cada uno de los meses del año. Se creará un array que sirva para rellenar dinámicamente con valores por defecto los elementos del formulario. Las temperaturas pueden tener valores decimales. Al enviar el formulario, el programa mostrará una tabla con los nombres de las ciudades ordenadas alfabéticamente y los datos
correspondientes a la temperatura máxima, mínima y temperatura media del año en cada ciudad.

  *Bonus: Validar mediante los controles adecuados y código JavaScript en un fichero externo, que el usuario no pueda introducir valores incompatibles, esto es, temperaturas inferiores a -15 grados ni mayores de 45 grados).*

6. (x2) Crear una pequeña agenda llamada *uAgenda.php* que, a través de un formulario, recoja los siguientes datos de contactos:
  - Nombre, teléfono (se debe seleccionar el tipo, fijo o móvil, a través de un control checkbox), correo electrónico, fecha de nacimiento y su imagen de forma opcional. A través de un botón se irán añadiendo los contactos, mostrando el servidor un mensaje sobre la ejecución del proceso.
  - Mediante otro botón se permitirá limpiar todos los datos del formulario. En caso de producirse un error se mostrará de nuevo el formulario remarcando el campo incorrecto.
  - Validar el formato de los correos electrónicos a través de una función de usuario que reciba el correo electrónico de cada contacto de la agenda y devuelva true si el correo termina en “@gmail.com”, “@educa.madrid.org”, o “@outlook.com” y false en caso contrario.
  - Implementar un botón que permita guardar la agenda en un fichero y una función que, al inicio del programa, permita cargar los datos desde aquel.
  - Por último, implementar un botón que permita visualizar en pantalla todos los contactos dados de alta en la agenda.

5. Desarrollar una aplicación que realice una pequeña encuesta (de dos opciones) a los usuarios, como por ejemplo: la tortilla de patata, ¿con cebolla o sin cebolla? No será necesario registrarse para poder votar, pero se deberá controlar que cada usuario sólo pueda hacerlo una única vez. Los resultados de la encuesta se deberán almacenar en un fichero en el servidor y se mostrarán por pantalla cada vez que un usuario vote, generando una gráfica mediante dos barras de colores.

6. Crear una secuencia de tres páginas donde la primera página solicite un nombre y contraseña de acceso al usuario (usuario *profe* y contraseña *1234*). En esta página se validarán los datos y, si el acceso es correcto, se accederá a la segunda página iniciando sesón. En caso contrario, se permanecerá en esta página y se mostrará un mensaje de error indicando el campo incorrecto. En la segunda página se mostrará un mensaje de bienvenida y, en caso de acceder sin registro, se redirigirá a la página inicial. La página tres contendrá el texto *Sólo accesible mediante sesión* y botón que permita cerrar sesión, redirigiendo posteriormente al usuario a la página uno.

   *Nota: Emplear la función header para redirigir al usuario a las distintas páginas*

7. Crear una página con un formulario de acceso (*login.php*), otra para registro (*registro.php*) y una página principal (*main.php*) para una tienda web online. La página de acceso debe tener un enlace a la página de registro y esta un enlace de retorno a la de acceso. En la parte de acceso, el programa tendrá dos usuarios ya creados: administrador (admin/admin) y usuario (usuario/usuaRIO), controlando en todo momento que no puedan realizarse accesos no autorizados a la página principal. En la parte de registro se solicitarán los datos personales, siendo libre su elección pero, al menos, se contemplarán el nombre de usuario y su contraseña. Los datos se enviarán a la misma página, donde se validarán y, en caso de ser inválidos, se volverá a mostrar el formulario destacando los campos incorrectos. Si los datos se validan correctamente, se redirigirá al usuario a la página de registro, donde se volverán a pedir el nombre y contraseña de acceso. Si el usuario accede correctamente, se mostrará un mensaje de bienvenida y su último acceso.

8. (x2) Partiendo del ejercicio anterior 
