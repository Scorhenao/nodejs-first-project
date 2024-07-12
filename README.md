# nodejs-first-project
## Preguntas de Reflexión y trabajo investigativo


1. ¿Qué es el filesystem (fs) en Node.js y para qué se utiliza?
    El filesystem es un módulo de Node.js que permite interactuar con el sistema de archivos por medio de una API con esta puedes leer, escribir, modificar y eliminar archivos y directorios

2. ¿Qué es un middleware en Express y cuál es su propósito?
    Un middleware es una función que se ejecuta entre la petición y la respuesta, es decir
    se ejecuta antes de que la petición llegue a la ruta y después de que la
    respuesta se envía al cliente. Su propósito es poder realizar acciones antes de que la petción llegue a la ruta y después la respuesta se envía al cliente.

3. ¿Qué es un endpoint en una API RESTful y cuál es su función?
    Un endpoint es una dirección URL que se utiliza para acceder a un recurso en una API

4. ¿Qué son los verbos HTTP y cuáles son los más comunes?
    Los verbos HTTP son los métodos que se utilizan para realizar una petición a un
    recurso en una API. Los más comunes son GET, POST, PUT, DELETE y PATCH.

5. ¿Qué es JSON y por qué es utilizado en las API RESTful?
    JSON es un formato de intercambio de datos que se utiliza para transmitir datos
    entre aplicaciones. Es utilizado en las API RESTful porque es un formato ligero
    y fácil de leer para los humanos y para las máquinas.

6. En lo que respecta al envio de datos a lo largo de los verbos http responde:
    - ¿Qué es el body de una petición?
    - ¿Qué es el body de una respuesta?
    - ¿Qué es el query de una petición?
    - ¿Qué es el params de una petición?

    respuestas:
    - El body de una petición es el contenido que se envía en el cuerpo de la
    petición, por ejemplo, un formulario HTML o un objeto JSON.

    - El body de una respuesta es el contenido que se envía en el cuerpo de la
    respuesta, por ejemplo, un objeto JSON o un archivo en formato binario.

    - El query de una petición es la parte de la URL que se utiliza para pasar
    parámetros a la petición, por ejemplo, ?param1=value1&param2=value2. Estos
    parámetros se utilizan para filtrar o ordenar los resultados de una petición.

    - El params de una petición es la parte de la URL que se utiliza para pasar
    parámetros a la petición, pero en este caso los parámetros se pasan
    después del nombre de la ruta, por ejemplo, /ruta/:param1/:param2.

7. En lo que respecta al verbo POST responde:
    - ¿Qué es un verbo POST y cuál es su propósito?
    - ¿Cuándo se utiliza un verbo POST?
    - ¿En qué se diferencia un verbo POST de los otros verbos HTTP como GET, PUT y DELETE?
    - ¿Como se envian datos en un verbo POST?

    respuestas:
    - Un verbo POST es un método HTTP que se utiliza para crear un recurso en una
    API. Su propósito es crear un nuevo recurso en una API.

    - Se utiliza un verbo POST cuando se quiere crear un nuevo recurso en una API.

    - Un verbo POST se diferencia de los otros verbos HTTP porque se utiliza para
    crear un nuevo recurso en una API, mientras que los otros verbos HTTP se
    utilizan para leer, actualizar o eliminar recursos en una API.

    - Por medio de promesas y convirtiendo la data del lenguaje de programacion a una
    cadena de texto como JSON y enviandola en el body de la peticion.

8. En lo que respecta al verbo GET responde:
    - ¿Qué es un verbo GET y cuál es su propósito?
    - ¿Cuándo se utiliza un verbo GET?
    - ¿En qué se diferencia un verbo GET de los otros verbos HTTP como POST, PUT y DELETE?

    respuestas:
    - Un verbo GET es un método HTTP que se utiliza para leer un recurso en una
    API. Su propósito es leer un recurso existente en una API.

    - Cuando necesitas consultar informacion de un servidor o un 
    recurso en especifico, se utiliza un verbo GET.

    - La diferencia de un metodo GET respecto a los demas metodos es
    que no modifica el estado del servidor, es decir, no crea, actualiza o elimina recursos en el servidor, solo lee recursos existentes en el servidor.

9. En lo que respecta al verbo PUT responde:
    - ¿Qué es un verbo PUT y cuál es su propósito?
    - ¿Cuándo se utiliza un verbo PUT?
    - ¿En qué se diferencia un verbo PUT de los otros verbos HTTP como POST, GET y DELETE?

    resupuestas:
    - Un verbo PUT es un método HTTP que se utiliza para actualizar un recurso en una
    API. Su propósito es actualizar un recurso existente en una API.

    - Un verbo PUT se utiliza cuandose quiere actualizar un recurso existente en una API.ç

    - El verbo PUT se diferencia de los demas verbos HTTP ya que
    actualiza un recurso existente en una API, mientras que los otros verbos HTTP se
    utilizan para crear, leer o eliminar recursos en una API.

10. En lo que respecta al verbo DELETE responde:
    - ¿Qué es un verbo DELETE y cuál es su propósito?
    - ¿Cuándo se utiliza un verbo DELETE?
    - ¿En qué se diferencia un verbo DELETE de los otros verbos HTTP como POST, GET y PUT?

    respuestas:
    - Un verbo DELETE es un método HTTP que se utiliza para eliminar un recurso en una
    API. Su propósito es eliminar un recurso existente en una API.

    - El verbo DELETE se utiliza cuandose quiere eliminar un recurso existente en una API.

    - Lo que diferencia el verbo DELETE de los demas verbos HTTP es
    que elimina un recurso existente en una API, mientras que los otros verbos HTTP
    se utilizan para crear, leer o actualizar recursos en una API.

11. ¿Qué es un status code y cuáles son los más comunes?

    El status code es
    un código de estado HTTP que se utiliza para indicar el resultado de una solicitud HTTP. Los códigos de estado más comunes son:

    - 200 OK: indica que la solicitud se ha procesado correctamente y que el recurso
    solicitado se ha devuelto correctamente.

    - 400 Bad Request: indica que la solicitud es incorrecta y que el servidor no puede
    procesarla.

    - 401 Unauthorized: indica que la solicitud no está autorizada y que el servidor
    requiere autenticación.

    - 403 Forbidden: indica que la solicitud está autorizada, pero que el servidor no
    permite el acceso al recurso solicitado.   

    - 404 Not Found: indica que el recurso solicitado no se encuentra en el servidor

    - 500 Internal Server Error: indica que ha ocurrido un error en el servidor y que
    no se puede procesar la solicitud.

12. ¿Cuales son los status code mas comunes para el verbo POST?

    - 201 Created: indica que la solicitud se ha procesado correctamente y que el recurso
    solicitado se ha creado correctamente.

    - 202 Accepted: indica que la solicitud se ha procesado correctamente, pero que el
    recurso solicitado no se ha creado aún.

    - 204 No Content: indica que la solicitud se ha procesado correctamente, pero que el
    recurso solicitado no tiene contenido.

13. ¿Cuales son los status code mas comunes para el verbo GET?

    - 200 OK: indica que la solicitud se ha procesado correctamente y que el recurso
    solicitado se ha devuelto correctamente.

    - 404 Not Found: indica que el recurso solicitado no se encuentra en el servidor

    - 500 Internal Server Error: indica que ha ocurrido un error en el servidor y que
    no se puede procesar la solicitud.


14. ¿Cuales son los status code mas comunes para el verbo PUT?

    - 200 OK: indica que la solicitud se ha procesado correctamente y que el recurso
    solicitado se ha actualizado correctamente.

    - 204 No Content: indica que la solicitud se ha procesado correctamente, pero que el
    recurso solicitado no tiene contenido.

    - 400 Bad Request: indica que la solicitud es incorrecta y que el servidor no puede
    procesarla.

    - 404 Not Found: indica que el recurso solicitado no se encuentra en el servidor

    - 500 Internal Server Error: indica que ha ocurrido un error en el servidor y que
    no se puede procesar la solicitud.


15. ¿Cuales son los status code mas comunes para el verbo DELETE?

    - 200 OK: indica que la solicitud se ha procesado correctamente y que el recurso
    solicitado se ha eliminado correctamente.

    - 204 No Content: indica que la solicitud se ha procesado correctamente, pero que el
    recurso solicitado no tiene contenido.

    - 400 Bad Request: indica que la solicitud es incorrecta y que el servidor no puede
    procesarla.

    - 404 Not Found: indica que el recurso solicitado no se encuentra en el servidor
    
    - 500 Internal Server Error: indica que ha ocurrido un error en el servidor y que
    no se puede procesar la solicitud.