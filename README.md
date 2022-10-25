# Glosario de terminos

Protocolo cors.

Disparadores de JavaScript.

Qué son los JSON.

Qué es un worker y service worker.

Qué son interfaces en PHP.



## Protocolo cors

Es una característica de seguridad del navegador que restringe las solicitudes HTTP de origen cruzado que se inician desde secuencias de comandos que se ejecutan en el navegador. Si los recursos de la API REST reciben solicitudes HTTP complejas de varios orígenes, debe habilitar la compatibilidad con CORS.

Por defecto, los navegadores permiten enlazar hacia documentos situados en todo tipo de dominios si lo hacemos desde el HTML o desde Javascript utilizando la API DOM.

![ (Cross-Origin Resource Sharing)](https://lenguajejs.com/javascript/peticiones-http/cors/cors.png)



## Disparadores de JavaScript.

El método trigger() activa el evento especificado y el comportamiento predeterminado de un evento (como el envío de un formulario) para los elementos seleccionados. Este método es similar al método triggerHandler(), excepto que triggerHandler() no desencadena el comportamiento predeterminado del evento.

![How to Trigger Click Event in Javascript - YouTube](https://i.ytimg.com/vi/jMIOlTL2veQ/maxresdefault.jpg)



## Qué son los JSON.

**JSON** ( **JavaScript Object Notation**) es un formato de texto sencillo para el intercambio de datos. Se trata de un subconjunto de la notación literal de objetos de JavaScript, aunque, debido a su amplia adopción como alternativa a XML, se considera un formato independiente del lenguaje.

Los JSON son cadenas - útiles cuando se quiere transmitir datos a través de una red. Debe ser convertido a un objeto nativo de JavaScript cuando se requiera acceder a sus datos. Ésto no es un problema, dado que JavaScript posee un objeto global JSON que tiene los métodos disponibles para convertir entre ellos.

![Te Decimos Qué Es JSON y Cómo Usarlo En Tu Sitio Web](https://www.hostinger.es/tutoriales/wp-content/uploads/sites/7/2020/01/json-value.jpg)

## Qué es un worker y service worker.

### Worker

Hacen posible ejecutar la operación de un script en un hilo en segundo plano separado de la ejecución el hilo principal de la aplicación web. La ventaja de esto es que un proceso laborioso puede actuar en un hilo separado, permitiendo al hilo principal (normlamente la UI) ejecutarse sin ser bloqueado o ralentizado.

![Decálogo de capacidades del digital worker - Think Big Empresas](https://empresas.blogthinkbig.com/wp-content/uploads/2019/10/digital-worker-2.png?fit=1200%2C527?w=800)

### ServiceWorker

Una ServiceWorker es capaz de alterar las respuestas del servidor, interceptar las peticiones del cliente, mandar información específica a ciertas direcciones, recibir notificaciones push, hacer actualizaciones aunque la página no esté abierta, y eventualmente se irán añadiendo otras capacidades a esta sección del navegador.

Lo que hace interesante es que a través de esta tecnología y la capacidad de actualizar y almacenar archivos en el caché del navegador, podemos ofrecer respuesta a peticiones aún sin internet.

![Service Workers: ¿Qué son y cómo se comen? | by Anuar Harb | Medium](https://miro.medium.com/max/1400/0*0kDS64pU8BNIDbSp)



## Qué son interfaces en PHP.

Las interfaces de objetos son contratos que han de cumplir las clases que las implementan. Contienen métodos vacíos que obligan a una clase a emplearlos, promoviendo así un estándar de desarrollo.

![image-20221024194640313](C:\Users\jpman\AppData\Roaming\Typora\typora-user-images\image-20221024194640313.png)