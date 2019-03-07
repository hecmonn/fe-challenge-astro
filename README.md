Prueba Front End Astro

En esta prueba trataremos de generar la creación de un servicio, replicando el flujo que utiliza puls.com

La aplicación debe de hacer los siguientes pasos:

1) Una pantalla que permita seleccionar servicios, crear 3 servicios, únicamente 1 tiene que ser funcional, los dos pueden ser placeholders
   Crear en ### src/components/SelectService.js

2) Una vez que seleccionamos el servicio, el usuario debe de tener un campo para ingresar su dirección. Esta dirección se debe de autocompletar con la API de Google Places (key enviado por correo).
   -> Si la dirección se encuentra afuera de México, mostrar un modal indicando al cliente que no ofrecemos servicios fuera del país.
   -> Si la dirección se encuentra dentro de México pasar al paso 3
   Crear en ### src/components/Address.js

3) Mostrar una pantalla donde le preguntemos al cliente cuáles son las instrucciones a seguir.
   -> Crear una validación que el campo no puede estar vacio.
   Crear en ### src/components/Instructions.js

4) Mostrar una pantalla de confirmación donde mostremos la dirección donde se realizará el servicio y las instrucciones a seguir en ésta.
   -> Agregar un boton de regresar a inicio
   Crear en ### src/components/Confirmation.js

5) Crear la lógica del flujo sobre ### src/components/index.js

6) Correr la aplicación sobre ###src/App.js

Es posible utilizar cualquier paquete de yarn.
