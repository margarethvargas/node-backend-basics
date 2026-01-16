¿Qué es Node.js?
Es un entorno de ejecucion que permite ejecutar js fuera del navegador. Se utiliza principalmente para el backend.

¿Qué significa que sea “single-threaded”?
Significa que Node js utiliza un solo hilo principal para ejecutar el codigo pero, atiende multiples operaciones concurrentes mediante programacion asincrona.


¿Qué es el event loop?
Es el cerebro de Node.js, se encarga de: revisar si hay tareas pendientes, ejecutarlas cuando esten listas y no bloquear el hilo principal.
Es el mecanismo que permite a Nodejs manejar tareas asincronas, como peticiones HTTP o acceso a base de datos, sin bloquear el hilo principal.
Event loop permite a Nodejs manejar multiples operaciones asincronas sin bloquear el hilo principal.
temas que maneja: peticiones HTTP, consulta a base de datos, timers, promesas (asyn, await)

¿Para qué se usa Node en empresas LATAM?
API Rest
Aplicaciones backend 
Microservicios
Integracion de servicios
