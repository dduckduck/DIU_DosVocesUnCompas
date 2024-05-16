# DIU24
Prácticas Diseño Interfaces de Usuario 2023-24 (Tema: .... ) 

Grupo: DIU1_01AABB.  Curso: 2023/24 
Updated: 11/2/2024

Proyecto: 
>>> Decida el nombre corto de su propuesta en la práctica 2 

Descripción: 

>>> Describa la idea de su producto en la práctica 2 

Logotipo: 
>>> Opcionalmente si diseña un logotipo para su producto en la práctica 3 pongalo aqui

Miembros
 * :bust_in_silhouette:   AA     :octocat:     
 * :bust_in_silhouette:  BB     :octocat:

----- 



>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. Elimine este texto desde la práctica 1


# Proceso de Diseño 

## Paso 1. UX User & Desk Research & Analisis 


![Método UX](img/Competitive.png) **1.a User Reseach Plan**
-----

>>> Describe el plan de User Research (cómo se planteas)  

![Método UX](img/Competitive.png) 1.b Competitive Analysis
-----

>>> Describe brevemente características de las aplicaciones que tienes asignadas, y por qué has elegido una de ellas 

![Método UX](img/Persona.png) 1.c Persona
-----

>>> Comenta brevemente porqué has seleccionado a esas personas y sube una captura de pantalla de su ficha  

![Método UX](img/JourneyMap.png) 1.d User Journey Map
----


>>> Comenta brevemente porqué has escogido estas dos experiencias de usuario (y si consideras que son habituales) 

![Método UX](img/usabilityReview.png) 1.e Usability Review
----
>>>  Revisión de usabilidad: (toma los siguientes documentos de referncia y verifica puntos de verificación de  usabilidad
>>>> SE deben incluir claramente los siguientes elementos
>>> - Enlace al documento:  (sube a github el xls/pdf) 
>>> - Valoración final (numérica): 
>>> - Comentario sobre la valoración:  (60-120 caracteres)


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
----


 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas

Reflejamos que puede expresar pensar o decir un usuario de nuestra web o de las propias webs del mismo nicho del mercado. Exponemos varios puntos de vista y vemos que podmeos evitar para no dar porblemas y que puntos no estan lo suficientemente explotados.<br />  
[Mapa Empatia](Entrega/Entregables/Empathy%20Map%20Practica%202.pdf)
    



![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----
### Abstract
Nuestra propuesta de valor consiste en ofrecer un servicio web que mitigue las carencias más comunes que suelen tener las páginas webs. En particular, queremos hacer hincapié en la relevancia y utilidad de la información alojada puesto que en muchas ocasiones esta no aparece de forma clara o está escondida detrás de un esquema de navegación anti intuitiva e inhumana. Pretendemos liberar la información de la basura de palabrejas usadas para SEO y enfocarnos en contenido genuino y valioso para los usuarios.

Nos gustaría ofrecer una experiencia limpia,simple, consistente, sólida y madura sin complicaciones innecesarias o distracciones superfluas. Queremos que nuestros usuarios en un par de clicks obtengan toda la información necesaria para poder tomar decisiones sin tener que llamar por teléfono o escribir correos suplicando por la información. 

Nuestra meta es crear un entorno web donde la información sea accesible, relevante y fácil de encontrar, brindando a nuestros usuarios una experiencia satisfactoria y enriquecedora cada vez que acuden a nuestro servicio.

---

### Funcionalidad
Nuestro servicio trata de los siguientes módulos:
- Usuarios:
son tanto las personas que están interesadas en alguna actividad (clientes) como las que ofrecen servicios (empresas)

- Actividades:
Son servicios ofertados por las empresas con la información como Fecha, Precio, Lugar, Hora

- Buscador:
Permite buscar por etiquetas o palabras claves alguna actividad relacionada, por ejemplo: “Cocina andalusí”

- Calendario
Agrupa las actividades ofrecidas por fechas, proporcionando una visión temporal. 

- Tinder de actividades (GastroBuddies)
Los usuarios de la app tendrán una funcionalidad para concretar actividades de la siguiente forma:
1º - Definirán cuando quieren realizar una actividad. Por ejemplo: Sábado a partir de las 9.
2º - Luego te empezaran a salir una serie de actividades con una pequeña descripción que cuadren con tus preferencias de búsqueda y podrás darle me gusta o rechazar la actividad.
3º - Cuando suficientes usuarios hayan dado me gusta una actividad se les mandará un correo o notificación con la información de la actividad y si la aceptan tendrán reservada dicha actividad junto con los demás usuarios.

[Descripcion](P2/Entrega/Entregables/descripcion%20y%20propuesta%20de%20valor.pdf)<br />  
[ScopeCanva](P2/Entrega/Entregables/scopecanva.pdf)

![Método UX](img/Sitemap.png) 2.b User Flow (task) analysis 
-----

![User Flow](P2/Entrega/Entregables/DIU_flow.png) 


![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----

En este sitemap se refleja la navegabilidad entre los diferentes elementos del sistema
![SiteMap](P2/Entrega/Entregables/DIU_sitemap.png)  

>>> Identificar términos para diálogo con usuario  

Término | Significado     
| ------------- | -------
  Usuario  | Persona que interactúa con el sistema
  Usuario registrado  | Persona que ha formalizado el proceso de registrarse
  Usuario cliente  | Persona que ha registrado su perfil como cliente. Puede reservar actividades pero no puede publicar una actividad
  Usuario empresa  | Persona que ha registrado su perfil como empresa. Puede publicar sus actividades
  Página principal  | Es el punto de partida, aquí se muestra una visión general sobre los contenidos que ofrece este sitio web.
  GastroBuddies  | Agrupa la funcionalidad del módulo GastroBuddies  
  Ver Buddies  | Muestra una serie de sugerencias de eventos acordes a las preferencias que el usuario indicó en su perfil  
  Ver actividades  | Muestra la información sobre las actividades en las que participa el usuario
  Preferencias  | Permite al usuario establecer sus preferencias que se utilizaran para las recomendaciones de actividades (Ver buddies)
  Iniciar sesión  | Permite al usuario identificarse en el caso de que esté registrado en el sistema
  Registrarse  | Permite al usuario registrarse en el sistema si aún no está registrado
  Calendario actividades  | Este módulo ofrece una visión temporal y espacial sobre las actividades que están registrados en el sistema
  Detalles de una actividad  | Muestra toda la información correspondiente a una actividad
  Reservar actividad  | Permite al usuario reservar una actividad en la que el usuario está interesado.
  Mi Perfil  | Módulo que engloba la funcionalidad de gestión de los datos del usuario
  Gestionar datos  | Permite al usuario modificar sus datos
Gestionar actividades  | Permite al usuario gestionar las actividades que ha reservado
  Añadir actividad  | Permite al usuario empresa añadir una actividad que se mostrará en el calendario de actividades
  Modificar actividad  | Permite al usuario empresa editar la actividad que ha añadido
  Cancelar actividad  | Permite al usuario empresa borrar una actividad que ha registrado previamente. En el caso de ser usuario cliente permite cancelar la actividad que ha reservado previamente
Borrar perfil | Permite al usuario registrado borrar su perfil según la legislación europea de protección de datos

![Método UX](img/Wireframes.png) 2.d Wireframes
-----

[Bocetos](P2/Entrega/Entregables/Bocetos.pdf)  

## Wireframes
### Desktop
![Desktop](P2/Entrega/Entregables/wireframe_Desktop.png)

### Ipad
![Ipad](P2/Entrega/Entregables/wireframe_iPad_Pro_11.png)

### Iphone
![Iphone](P2/Entrega/Entregables/wireframe_iPhone_13_&_14.png)


## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Si diseña un logotipo, explique la herramienta utilizada y la resolución empleada. ¿Puede usar esta imagen como cabecera de Twitter, por ejemplo, o necesita otra?


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto


## Paso 5. Exportación & evaluación con Eye Tracking 

Exportación a HTML/Flutter
-----

![Método UX](img/eye-tracking.png))  5.b Eye Tracking method 

>>> Indica cómo diseñas experimento y reclutas usuarios (uso de gazerecorder.com)  

Diseño del experimento 
----

>> Uso de imágenes (preferentemente) -> hay que esablecer una duración de visualización y  
>> fijar las áreas de interes (AoI) antes del diseño. Planificar qué tarea debe hacer el usuario (buscar, comprar...) 


![experimento](img/experimentoET.png)  
>> cambiar img por tu diseño de experimento  

>> Recordar que gazerecorder es una versión de pruebas: usar sólo con 3 usuarios para generar mapa de calor (recordar que crédito > 0 para que funcione) 

Resultados y valoración 
-----



>> Cambiar por tus resultados
![Resultado](img/resultadoET.png)  



## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png) 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 





5.) Conclusion de EVALUACION (A/B testing + usability report + eye tracking) 
----


>> recupera el usability report de tu práctica (que es el caso B de los asignados a otros grupos) 
>> con los resultados del A/B testing, de eye tracking y del usability report:
>>  comentad en 2-3 parrafos cual es la conclusion acerca de la realización de la práctica y su evaluación con esas técnicas y que habéis aprendido






## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













