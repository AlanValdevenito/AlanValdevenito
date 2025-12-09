</div>

<h2 align="center">Informacion sobre mi</h2>

<div align="center">
  
  Soy estudiante de [Ingeniería Informática](https://cms.fi.uba.ar/uploads/RESCD_2023_526_Informatica_Plan_2023_Aprobacion_15d3cee700_6e3b075bd4.pdf) en la Universidad de Buenos Aires (UBA), tengo 24 años y actualmente me quedan 5 materias y el trabajo profesional para terminar la carrera.
  
</div>

<h2 align="center">Lenguajes de programacion y herramientas</h2>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/git/git-original.svg" alt="git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/github/github-original.svg" alt="git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/gitlab/gitlab-original.svg" alt="git" width="40" height="40"/>
</p>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/c/c-original.svg" alt="c" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/ruby/ruby-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/rust/rust-plain.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/java/java-original.svg" alt="java" width="40" height="40"/> 
</p>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/postgresql/postgresql-original.svg" alt="java" width="40" height="40"/> 
</p>

<h2 align="center">Proyectos de FIUBA</h2>

<div align="center">
  <h3 align="center">Worms 2D: Juego multijugador</h3>
  <p align="center">
    Destacó como proyecto principal un juego multijugador que se desarrolló de forma colaborativa como parte de un trabajo universitario, el cual consiste en una remake del Worms 2D.
    
  El proyecto fue desarrollado en C++, tiene una simulación física usando el framework Box2D y la interfaz se creó usando las librerías de QT y SDL2pp. Como metodología de trabajo utilizamos Scrum. Se utiliza programación concurrente orientada a objetos y sockets TCP/IPv4 bloqueantes como protocolo de comunicación.
    
  El proyecto tiene su propia <a href="https://alanvaldevenito.github.io">página web</a> donde se puede encontrar más información acerca del proyecto, acceder a su <a href="https://github.com/AlanValdevenito/Worms">repositorio</a> de GitHub y ver un <a href="https://www.youtube.com/watch?v=cXs05yU9hYE">tráiler</a> del mismo.

Por ultimo, antes de comenzar el desarrollo de este proyecto se realizaron dos <a href="https://github.com/AlanValdevenito/Taller-De-Programacion-I/tree/main/ENTREGAS">pruebas de concepto</a> individuales. Una primer prueba de concepto sobre <a href="https://github.com/AlanValdevenito/Taller-De-Programacion-I/tree/main/ENTREGAS/SOCKETS">Sockets</a> y una segunda prueba de concepto sobre <a href="https://github.com/AlanValdevenito/Taller-De-Programacion-I/tree/main/ENTREGAS/THREADS">Threads</a>.
</div>

<div align="center">

  <h3 align="center">Turnero</h3>

  <p align="center">
    Destacó como proyecto la resolucion de una problematica de negocio real mediante la implementación de una solución basada en software. A diferencia de otros proyectos académicos, no existía un enunciado ni una lista de funcionalidades predefinidas. Tuvimos un "cliente" cuyo rol fue ocupado por uno de los miembros del equipo docente con un problema de negocio. A partir de esto, nosotros tuvimos que relevar el problema y plantear un proyecto para solucionarlo. Es decir, nosotros tuvimos que identificar las funcionalidades, darles forma de User Stories, validarlas con el cliente, diseñar, codear, testear e implementar.

  La problemática de negocio consistía en la **automatización de los turnos médicos en un hospital**. Nuestra solución fue desarrollar un sistema compuesto por dos elementos principales: una **API REST**, responsable de la gestión de usuarios, médicos y turnos, y un **BOT de Telegram**, que funcionó como interfaz directa para los pacientes. De este modo, los pacientes podían solicitar, cancelar y consultar turnos médicos de manera sencilla, mientras que la API garantizaba la correcta administración de la información.
  </p>

  <details>
  <summary><b>Más detalles acerca del proyecto</b></summary>
  <br>

  Utilizamos la técnica de **[User Story Mapping](https://10pines.gitbook.io/desarrollo-de-software-agil-en-10pines/product-discovery#user-story-mapping)** para relevar las funcionalidades. 

  El proyecto se desarrolló en el transcurso de **tres semanas**, trabajando con iteraciones semanales bajo el estilo de **Extreme Programming (XP)**. Esto implicó planificar tanto a alto nivel, mediante un release plan inicial, como semana a semana, dando visibilidad en un esquema de entrega continua y al final de la semana revisar lo realizado tanto a nivel producto como a nivel proceso. 
  
  El flujo de trabajo fue el siguiente: primero relevamos las funcionalidades y presentamos un release plan a nuestro Product Owner (PO), quien definió cuál sería el MVP. A partir de allí, en cada iteración (con excepción de la primera, que tuvo solo Planning), los jueves realizábamos **Review, Planning y Retrospective**, y durante la semana trabajábamos en un esquema de entrega continua. Esto significaba que cada funcionalidad (User Story) debía estar validada en producción antes de llegar a la Review, para lo cual definimos un proceso claro: Al comienzo de cada iteracion le comunicabamos a nuestro PO el alcance de la iteracion (es decir, que US entraban en la iteracion donde cada US tenia su estimacion relativa). Antes de comenzar con el desarrollo de cada User Story debíamos enviar al PO los **Gherkin** correspondientes, que él validaba y autorizaba. Una vez que la funcionalidad estaba completa, se desplegaba en el ambiente de test para que el PO pudiera testearla y, tras su aprobación, se realizaba el deploy a producción. De esta manera, siempre llegábamos a la Review con todas las funcionalidades ya disponibles en producción y validadas por el cliente. 

  En cuanto a las metodologías aplicadas, trabajamos con **[BDD y TDD](https://drive.google.com/file/d/1whj-ZLlxVoHNaUnE6a8ckv_XHj9L7wg1/view?usp=sharing)**. La **forma de trabajo** se basó en integración continua, desarrollo en un único branch con trunk-based development, pair y mob programming, y un esquema de entrega continua. La colaboración y el versionado del código se gestionaron en **GitLab**, lo que nos permitió organizar el trabajo de manera centralizada y garantizar la integración continua. También gestionamos el despliegue en **dos ambientes cloud** diferenciados: uno de prueba y otro de producción.

  En cuanto a diseño e implementación, aplicamos **arquitectura hexagonal** para desacoplar las capas de dominio de las de infraestructura, el **patrón Repository** para manejar el acceso a datos y los principios de **12-Factor App**.

  La implementación técnica se realizó íntegramente en **Ruby**, tanto para la API REST como para el BOT de Telegram. La API fue desarrollada con **Sinatra** como microframework web, apoyándose en la gema **Faraday** para realizar solicitudes HTTP, y utilizando **Sequel** como ORM para la interacción con la base de datos. Como base de datos relacional utilizamos **PostgreSQL**. En cuanto a herramientas de desarrollo, empleamos **Cucumber y Gherkin** para las pruebas de aceptación, **RSpec** para las pruebas unitarias, **SimpleCov** para medir la cobertura del código, **Rubocop** para análisis estático y estilo, y **Rake** para la automatización de tareas comunes. 
  
  En el aspecto de infraestructura, el proyecto utilizó **[Neon](https://neon.com/)** como proveedor de base de datos, **[Sumologic](https://www.sumologic.com/)** para la gestión de logs y **Kubernetes** para el despliegue en la nube. 

  La arquitectura general del proyecto puede consultarse <a href="https://drive.google.com/file/d/1LjbY6dtETmhxP2npj-uCvuaMqJUVTmLG/view?usp=sharing" target="_blank">aquí</a>.

  En relación con las funcionalidades, identificamos y desarrollamos una serie de **User Stories** que abarcaban tanto las necesidades del hospital como las de los pacientes.

  | ID   | Descripción                                                                 |
  |------|-----------------------------------------------------------------------------|
  | US19 | Como hospital quiero dar de alta una especialidad                          |
  | US18 | Como hospital quiero dar de alta a un médico                               |
  | US7  | Como hospital quiero consultar los turnos que tiene un paciente            |
  | US3  | Como paciente quiero poder reservar un turno en un horario disponible      |
  | US17 | Como paciente quiero poder registrarme utilizando mi email                 |
  | US30 | Como hospital quiero consultar los turnos que tiene un médico              |
  | US6  | Como paciente quiero ver mi historial de turnos                            |
  | US14 | Como hospital quiero que el sistema respete feriados                       |
  | US5  | Como paciente quiero ver mis próximos turnos                               |
  | US26 | Como hospital quiero modificar el estado de un turno                       |
  | US31 | Como paciente no puedo seleccionar más de 1 turno en un mismo listado      |
  | US2  | Como paciente quiero poder reservar un turno por especialidad              |
  | US22 | Como hospital quiero dar de baja un paciente                               |
  | US20 | Como hospital quiero dar de baja a un médico                               |
  | US15 | Como hospital quiero evitar superposición de turnos                        |
  | US11 | Como hospital quiero penalizar acceso a turnos según historial de asistencia|
  | US12 | Como hospital quiero que los turnos solo sean visibles a personal autorizado|
  | US16 | Como hospital quiero restringir cantidad de turnos por especialidad        |
  | US24 | Como hospital quiero modificar una especialidad                            |
  | US4  | Como paciente quiero cancelar un turno reservado                           |
  | US21 | Como hospital quiero dar de baja una especialidad                          |

  Cada una de estas funcionalidades fue pensada, validada, desarrollada y puesta en producción siguiendo el esquema de trabajo descrito anteriormente.

  </details>

   Se puede acceder a sus dos repositorios de GitHub. Por un lado tenemos el <a href="https://github.com/AlanValdevenito/turnero-api">repositorio de la API</a> y por otro el <a href="https://github.com/AlanValdevenito/turnero-bot-telegram">repositorio del BOT de Telegram</a>

   Mencionamos que los repositorios del proyecto fueron copiados en GitHub para su difusion, pero el desarrollo estuvo originalmente en GitLab.

</div>

<div align="center">
  <h3 align="center">Compilador de Lox en Rust</h3>
  <p align="center">
   
  Destacó como proyecto la implementación de un compilador de [Lox](https://craftinginterpreters.com/the-lox-language.html) en [Rust](https://doc.rust-lang.org/book/) teniendo como referencia la segunda parte del libro [Crafting Interpreters](https://craftinginterpreters.com/contents.html) de Robert Nystrom.

  ¿Que es Lox?. Es un lenguaje de programación creado por Robert Nystrom para el libro. Es un lenguaje específicamente diseñado para enseñar cómo construir intérpretes y máquinas virtuales. Lox es un lenguaje dinamico, tipado dinamicamente de alto nivel con sintaxis parecida a JavaScript. 

  A diferencia del libro (donde se implementa en C y con un compilador de una sola pasada) se implemento en Rust y con una separación de las fases de parseo y compilacion.

  El compilador tiene su <a href="https://github.com/ricomateo/lox-compiler">repositorio</a> de GitHub y también se puede acceder a las [slides](https://docs.google.com/presentation/d/1FyM-nl8sC7lRgMgru87uVzur-gM--kwyu6buONDd5TI/edit?slide=id.g3a2a591218e_0_22#slide=id.g3a2a591218e_0_22) que fueron usadas para su presentación.

  Adicionalmente, pude contribuir en mejoras a [Plox](https://github.com/FdelMazo/plox) agregando el operador `++` en los PR [#5](https://github.com/FdelMazo/plox/pull/5) y [#9](https://github.com/FdelMazo/plox/pull/9). Plox es un interprete de Lox en Python utilizado en las clases y esta basado en la primera parte del libro [Crafting Interpreters](https://craftinginterpreters.com/contents.html) de Robert Nystrom
</div>

<div align="center">
  <h3 align="center">File Transfer</h3>
  <p align="center">
    Destacó como proyecto la implementación de un File Transfer que se desarrolló de forma colaborativa como parte de un trabajo universitario para la materia Redes, teniendo como objetivo la comprensión y la puesta en práctica de los        conceptos y herramientas necesarias para la implementación de un protocolo RDT.
   
   En este proyecto se desarrollo una aplicación de arquitectura cliente-servidor que implementa la funcionalidad de transferencia de archivos mediante las operaciones upload (Transferencia de un archivo del cliente hacia el servidor) y download (Transferencia de un archivo del servidor hacia el cliente). La aplicacion fue desarrollada en Python utilizando la libreria estandar de sockets, donde la comunicacion entre procesos fue implementada utilizando UDP como protoclo de capa de transporte. Además, para lograr una transferencia confiable al utilizar el protocolo UDP, se implemento una versión utilizando el protocolo Stop & Wait y otra versión utilizando el protocolo Go-Back-N. Por último, el servidor es capaz de procesar de manera concurrente la transferencia de archivos con múltiples clientes.
    
  Se puede acceder a su <a href="https://github.com/AlanValdevenito/TP1-Redes">repositorio</a> de GitHub, donde se encuentra la implementacion de la aplicacion, el <a href="https://github.com/AlanValdevenito/TP1-Redes/blob/main/enunciado.pdf">enunciado</a> con mas detalles y el <a href="https://github.com/AlanValdevenito/TP1-Redes/blob/main/informe.pdf">informe</a> del mismo.
</div>

<div align="center">
  <h3 align="center">Machine Learning</h3>
  <p align="center">
    Destacó como proyecto un modelo de Machine Learning sobre la predicción de si un hongo es comestible o no. El objetivo es explicar y predecir la variable class, que vale p, si el hongo es venenoso (poisonous), o e, si el hongo es comestible (edible).

  El proyecto se divide en 4 partes. La primer parte es un <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/blob/main/ENTREGAS/TP2/PARTE-1/analisis-exploratorio.ipynb">Analisis Exploratorio</a> de los datos, la segunda parte es un modelo de <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/blob/main/ENTREGAS/TP2/PARTE-2/machine-learning-baseline.ipynb">Machine Learning Baseline</a>, la tercer parte es un clasificador basado en <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/blob/main/ENTREGAS/TP2/PARTE-3/random-forest.ipynb">Random Forest</a> y por ultimo un modelo de <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/blob/main/ENTREGAS/TP2/PARTE-4/machine-learning.ipynb">Machine Learning</a> que no se haya utilizado anteriormente, con busqueda de hiper-parametros.

    
  Se puede acceder a su <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/tree/main/ENTREGAS/TP2">repositorio</a> de GitHub, donde se encuentra la implementacion de estos modelos, el <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/blob/main/ENTREGAS/TP2/ENUNCIADO.pdf">enunciado</a> con mas detalles y el <a href="https://github.com/AlanValdevenito/Organizacion-de-Datos/blob/main/ENTREGAS/TP2/dataset.zip">dataset</a> del mismo.
</div>

<div align="center">
  <h3 align="center">Ahorcado</h3>
  <p align="center">
    Destacó como proyecto la implementación de un Ahorcado que se desarrolló de forma colaborativa como parte de un trabajo universitario para la materia Ingenieria de Software I, teniendo como objetivo la comprensión y la puesta en práctica de los conceptos y herramientas vistas en la materia.
   
   La aplicacion fue desarrollada en Python, utilizando como metodologia de trabajo Scrum. Se tuvieron reuniones semanales, donde se aplico el concepto de Daily y Retrospectiva. Además, se crearon issues por semana para cada integrante del equipo, las cuales estaban estimadas mediante Story Points para definir la prioridad y el tamaño de estas. Por otro lado, se hicieron prototipos para trasmitirle la idea del diseño al cliente.
    
  Se puede acceder a su <a href="https://github.com/AlanValdevenito/Proyecto-AnInfo">repositorio</a> de GitHub, donde se encuentra la implementacion de la aplicacion.
</div>

<div align="center">
  <h3 align="center">Teoría de Algoritmos</h3>
  <p align="center">
    Destacó la realización de trabajos prácticos correspondientes a la materia <a href="https://algoritmos-rw.github.io/tda_bg/">Teoría de Algoritmos</a>, donde se estudiaron los siguientes temas:
  </p>

  <table style="margin: 0 auto; border-collapse: collapse; text-align: center;">
    <tbody>
      <tr><td>1.</td><td>División y Conquista avanzada</td></tr>
      <tr><td>2.</td><td>Algoritmos Greedy</td></tr>
      <tr><td>3.</td><td>Programación Dinámica</td></tr>
      <tr><td>4.</td><td>Backtracking</td></tr>
      <tr><td>5.</td><td>Programación Lineal</td></tr>
      <tr><td>6.</td><td>Redes de Flujo</td></tr>
      <tr><td>7.</td><td>Reducción de problemas</td></tr>
      <tr><td>8.</td><td>Clases de Complejidad</td></tr>
    </tbody>
  </table>
  
  <p align="center">
    Se realizaron 3 trabajos prácticos grupales que evaluaron el desarrollo y análisis de los distintos algoritmos.
   
   Se puede acceder a su <a href="https://github.com/AlanValdevenito/Teoria-de-Algoritmos-TPS">repositorio</a> de GitHub, donde se encuentra el desarrollo y análisis de cada algoritmo.

   También se puede acceder a otro <a href="https://github.com/AlanValdevenito/Teoria-de-Algoritmos">repositorio</a> de GitHub, donde se encuentran los ejercicios que realice para el estudio y práctica de la materia.
  </p>
</div>

<h2 align="center">Estadisticas</h2>

<p align= "center">
  <img height= "150" src="https://github-readme-stats.vercel.app/api?username=AlanValdevenito&theme=react&show_icons=true&include_all_commits=true" />
  <img height= "150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlanValdevenito&theme=react&layout=compact" />
</p>

<h2 align="center">Contacto</h2>
<div align="center">
  
  [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alan-ezequiel-valdevenito-a96299279)
  [![Outlook](https://img.shields.io/badge/Outlook-blue?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:AlanEzequielValdevenito@outlook.com)
  
</div>
