# EXFINAL-API

1. Para que se puede usar python en lo que respecta a Datos. Dar 5 casos y explicar brevemente
2. ¿Como se diferencian FLASK de DJANGO? Argumentar
3. ¿ Que es una API? Explicar en sus propias palabras
4. ¿ Cual es la principal diferencia entre REST y WebSockets?
5. Describir un ejemplo de API comercial y como funciona - usar otros ejemplos no vistos en el curso

1.
a) En datos puede usarse ejemplo para automatizar reportes usando librerias conocidas como pandas y openpyxl, esto permite automatizar procesos ETL
b) Para analizar mensajes en campañas de marketing, discursos de politicos, speechs en grupos grandes etc usando librerias que pemitan NLP, para analisis de sentimientos, etc.
c) Para realizar procesos automaticos de acceso a distintas paginas web, programando los clicks y digitacion que esta tengan que hacer (ejm Selenium)
d) Se puede usar tambien para el analisis de comportamiento del cliente en base a sus compras, para ver sus gustos, preferencias, segundas opciones, etc.
e) Para evaluar una persona que quiere sacar credito, ver su historial crediticio, puntualidad de pagos, etc. que ayuden a tomar decisiones

2. Flask es un microframework de Python para proyectos menores mientras Django es un framework con mayor alcance que usa librerias externas, Flask es de peso mas ligero pero tambien menos seguro a diferencia de Django lo cual tambien le permite a Django adaptarse a proyectos de grandes cargas

3. API o Interfaz de programacion de aplicaciones es una pieza de codigo que permite a dos aplicaciones comunicarse entre si para compartir informacion, permite la integracion de sistemas y funciona como un puente que conecta diversos tipos de software

4. REST se basa en HTTP para construir las APIs, utilizado en su mayoria para comunicaciones cliente-servidor de tipo "request-response", su alcance va mas para aplicaciones CRUD
   WebSockets va mas para una comunicación bidireccional en real time decision entre cliente y servidor, manteniendo una conexión persistente y es mejor para aplicaciones en tiempo real como chats o notificaciones.

5. Un api comercial vendria a ser la PEXELS API, que permite a sus usuarios acceder a un conjunto de fotos y videos gratuitos alimentado por fotografos de todo el mundo, prinicipalmente usada para integrar contenido visual en contenidos web o aplicaciones sin la preocupacion de los derechos de autor
   Otros ejemplos:
   PayPal API
   Google Maps API
   Spotify API
   Linkedin API, etc
