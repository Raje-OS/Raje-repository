<div align="center">

## Universidad Peruana de Ciencias Aplicadas

![logo](Report_Assets/UPC_logo_transparente.png)

#### Nombre del curso: Desarrollo de aplicaciones Open Source

##### Carrera: Ingeniería de Software

##### Nombre del profesor: Hugo Allan Mori Paiva

##### NRC: 4334

#### "Informe de Trabajo Final"

##### Nombre de la Startup: Caleta Innovations

##### Nombre del Producto: Raje

#### Integrantes

U20<br>
Cabanillas Meza Jose Mateo U202311458<br>
Verona Flores Italo Sebastian U20221E617<br>
U20<br>
Sarmiento Medina Loreley U202310005<br>

# *Abril de 2025*

</div>

## Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TP</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TB2</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TF</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Contents

- [Student Outcome](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivos](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
        - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
        - [4.7.2. Class Dictionary](#472-class-dictionary)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Caleta Innovations es una startup enfocada en revolucionar la forma en que las personas expresan sus opiniones y acceden
a contenido literario y audiovisual. En Caleta Innovations, valoramos la libertad de expresión y creemos en la
importancia de que cada voz sea escuchada sin filtros. Nos dedicamos a ofrecer soluciones innovadoras que permitan a
nuestros usuarios explorar una amplia variedad de contenido, mientras se sienten libres para compartir sus opiniones
auténticas.

Misión: Nuestra misión es empoderar a las personas para que puedan dar sus opiniones de manera sincera y sin censura,
mientras disfrutan de un acceso más amplio y diverso a contenido literario y audiovisual.

Visión: Nos vemos como una empresa líder en la creación de un entorno donde las opiniones auténticas y sin filtros son
el motor de una comunidad vibrante y dinámica. Aspiramos a ser la referencia global para aquellos que buscan compartir
sus perspectivas de manera genuina, enriqueciendo el acceso a contenido diverso y creando un espacio donde cada voz
tiene un impacto real y duradero.

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <thead>
    <tr>
      <th>Integrantes</th>
      <th>Perfil de Integrante</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="Report_Assets/integrante1.png" alt="Integrante 1" width="100"/></td>
      <td></td>
    </tr>
    <tr>
       <td><img src="Report_Assets/integrante2.png" alt="Integrante 2" width="100"/></td>
      <td> Jose Mateo Cabanillas Meza
        - Ingeniería de Software-u202311458 
 
Mi nombre es Mateo Cabanillas y en la 
actualidad estoy cursando el quinto ciclo de 
la carrera de ingeniería de software con una 
mente creativa y una actitud colaborativa. 
Mi amor por la programación y la 
resolución de problemas me impulsa a 
explorar nuevas soluciones y aportar ideas 
frescas a los proyectos. Como compañero de 
equipo, soy amable, atento y siempre estoy 
dispuesto a ayudar. Creo firmemente en la 
importancia de la comunicación efectiva y 
la colaboración para lograr resultados 
excepcionales. </td>
    </tr>
    <tr>
      <td><img src="Report_Assets/integrante3.png" alt="Integrante 3" width="100"/></td>
      <td></td>
    </tr>
    <tr>
      <td><img src="Report_Assets/integrante4.png" alt="Integrante 4" width="100"/></td>
      <td></td>
    </tr>
     <tr>
    <td><img src="Report_Assets/integrante5.png" alt="Integrante 5" width="100"/></td>
    <td>Soy Loreley Sarmiento Medina con codigo de estudainte U202310005 y estudio la carrera de Ingeniería de Software y me especializo en aportar soluciones tecnológicas integrales dentro de equipos multidisciplinarios. Cuento con sólidos conocimientos en el modelado de wireframes y mockups utilizando Figma, lo que me permite contribuir eficazmente en la etapa de diseño de interfaces centradas en el usuario. Además, tengo experiencia en el modelado de bases de datos, facilitando la organización y estructura lógica de la       información. Poseo conocimientos intermedios en HTML y CSS, lo cual me permite colaborar en el desarrollo de interfaces web funcionales y visualmente atractivas. También tengo una base sólida en lenguajes de programación, lo que me permite comprender e implementar soluciones tanto en el frontend como en el backend, aportando al desarrollo integral del producto</td>
  </tr>
  </tbody>
</table>

## 1.2. Solution Profile

Raje de Caleta Innovations es una plataforma innovadora que permite a los usuarios expresar 
sus opiniones de manera auténtica y sin filtros sobre películas, series, libros y más. Inspirada 
en la jerga latina "rajar," que significa hablar sin rodeos, Raje ofrece un espacio donde la 
libertad de expresión es fundamental. Además, la plataforma les muestra dónde está disponible 
el contenido, ya sea en plataformas de streaming o librerías. Los usuarios pueden rankear el 
contenido que consumen, dejar opiniones sinceras, y recibir recomendaciones personalizadas. 
Además, podrán ver la lista de sus opiniones y calificaciones, así como el contenido que han 
consumido, directamente en su perfil. Con un enfoque en la autenticidad, Raje redefine la 
manera en que las personas interactúan con el entretenimiento, fomentando una comunidad 
dinámica y vibrante donde cada voz cuenta. 

### 1.2.1. Antecedentes y problemática

<table>

  <tbody>
    <tr>
      <td> What ( Qué ) </td>
      <td>En el área del entretenimiento digital, los usuarios buscan cada vez más plataformas 
donde puedan descubrir y compartir opiniones sobre películas, series y libros. Sin 
embargo, las opciones disponibles suelen estar limitadas por filtros y políticas de 
moderación que restringen la libertad de expresión y la autenticidad de las opiniones. 
Además, muchas de las aplicaciones disponibles carecen de funcionalidades clave, 
como la ausencia de perfiles y una interfaz para explorar las opiniones de otros usuarios. 
La falta de una aplicación adecuada a opiniones de películas, series y libros limita al 
público a tomar decisiones informadas. Sin un lugar en el que los usuarios expresen y 
lean opiniones auténticas se pierde la diversidad de perspectivas que enriquece la 
experiencia de descubrir nuevo contenido. Por ende, se restringe el acceso a un amplio 
conjunto de opiniones, lo cual afecta la experiencia general de entretenimiento y la 
capacidad de descubrir contenido relevante. </td>
    </tr>
    <tr>
      <td> When ( Cuándo ) </td>
      <td> El problema aparece cuando los usuarios quieren buscar de 
opiniones auténticas sobre películas, series y libros. A menudo, ellos se enfrentan a la 
frustración de encontrar reseñas moderadas en las plataformas existentes. En 
consecuencia, los usuarios no pueden evaluar de manera precisa si un contenido se 
alinea con sus intereses, porque las reseñas disponibles a menudo están influenciadas 
por restricciones. </td>
    </tr>
    <tr>
      <td> Where ( Dónde ) </td>
      <td> Los problemas de la falta de una aplicación que permita opiniones de 
películas, series y libros sin filtros ni censura se aprecia en múltiples lugares, como 
plataformas de streaming, redes sociales, sitios de crítica y reseñas, foros en línea, etc. 
En estas plataformas, las opiniones de los usuarios a menudo están sujetas a moderación 
o políticas que restringen la libre expresión. Esta situación limita el acceso a una 
diversidad de perspectivas que afecta la capacidad de los usuarios para descubrir 
opiniones auténticas. </td>
    </tr>
    <tr>
      <td> Who ( Quién ) </td>
      <td>  Esta problemática afecta a diversos grupos de personas. En primer 
lugar, los espectadores y lectores que buscan opiniones para decidir qué contenido 
consumir se ven limitados por la falta de un espacio que ofrezca críticas genuinas. 
También impacta a críticos independientes o aficionados, quienes no tienen una 
plataforma adecuada para expresar sus opiniones sin temor a la censura. Además, las 
comunidades de nicho con intereses específicos enfrentan dificultades para encontrar y 
compartir opiniones relevantes que se alineen con sus gustos únicos.  </td>
    </tr>
    <tr>
      <td> Why ( Por qué ) </td>
      <td> La causa principal del problema es la falta de espacios que prioricen 
la autenticidad y la libertad de expresión, lo que lleva a una interacción superficial o 
condicionada entre los usuarios y sus comunidades. Las plataformas tradicionales 
pueden estar influenciadas por agendas comerciales, lo que diluye la sinceridad de las 
opiniones compartidas. </td>
    </tr>
     <tr>
      <td> How ( Cómo) </td>
      <td> Utilizando una aplicación que te permite no solo expresar tus opiniones 
sobre contenido audiovisual y literario, sino también leer las críticas de otros usuarios. </td>
    </tr>
     <tr>
      <td> How much ( Cuánto ) </td>
      <td> </td>
    </tr>
  </tbody>
</table>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
Hoy en día, millones de personas buscan recomendaciones auténticas sobre libros, películas y series antes de decidir qué consumir. Sin embargo, las plataformas actuales están llenas de filtros, políticas de moderación o algoritmos que limitan la libertad de expresión. Esto impide que los usuarios compartan opiniones sinceras y que descubran contenido relevante basado en experiencias reales.

Además, muchos consumidores se sienten frustrados porque no pueden dejar reseñas completas ni recibir sugerencias personalizadas que realmente se ajusten a sus gustos. La ausencia de perfiles, historial de reseñas o interacción entre usuarios reduce la calidad de la experiencia.

Del lado de los creadores o distribuidores de contenido, como dueños de librerías o plataformas de streaming, también hay una brecha. No cuentan con herramientas para conectar directamente con su audiencia a través de opiniones genuinas, ni aprovechar esa data para mejorar sus recomendaciones o promociones.

#### 1.2.2.2. Lean UX Assumptions

##### Opiniones auténticas tienen valor
Los usuarios valoran más una opinión real, aunque sea crítica, que una reseña genérica o influenciada por intereses comerciales. Quieren sentirse parte de una comunidad donde puedan expresarse con libertad y conocer lo que piensan otros usuarios parecidos a ellos.

##### Simplicidad y personalización en la experiencia
Los usuarios desean una plataforma que les permita explorar contenido fácilmente, con recomendaciones ajustadas a sus gustos reales. Si tienen un perfil personal donde pueden ver sus opiniones, calificaciones y descubrimientos, se sentirán más identificados con la plataforma y volverán con más frecuencia.

##### Integración con librerías y plataformas
Dueños de librerías y administradores de plataformas de streaming están interesados en conocer las opiniones reales de los usuarios. Si pueden acceder a esta información de manera organizada y con análisis útiles, podrán adaptar su oferta y conectar mejor con sus públicos objetivos.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Opinión libre y sin censura
Creemos que si brindamos a los usuarios un espacio donde puedan publicar sus opiniones sin censura, se generará un mayor sentido de pertenencia y autenticidad. Esto podría incrementar en un 20 % el número de reseñas activas por usuario al mes, medido a través de su historial de participación.

##### Perfil personalizado con historial
Creemos que si cada usuario puede tener un perfil que almacene sus opiniones, calificaciones y el contenido que ha consumido, se fortalecerá el compromiso con la plataforma. Esto se reflejará en un aumento del 25 % en visitas recurrentes por usuario, medido por sesiones activas semanales.

##### Valor para negocios y creadores de contenido
Creemos que si los dueños de librerías y plataformas de streaming tienen acceso a análisis de tendencias y opiniones, podrán adaptar mejor su catálogo y promociones. Esto se medirá por la tasa de participación de estos actores en la plataforma y el número de colaboraciones activas generadas.
#### 1.2.2.4. Lean UX Canvas

### 1.3. Segmentos objetivos

1. Consumidores de contenido multimedia 
Este segmento incluye a personas apasionadas por películas, libros, series que buscan un 
espacio para compartir opiniones auténticas y recibir recomendaciones personalizadas en Raje.

2. Dueños de Librerías 
Los dueños de librerías pueden conectar con lectores apasionados a través de Raje, 
promocionando sus libros en función de reseñas y calificaciones, y ofreciendo lanzamientos y 
eventos alineados con los intereses de los usuarios.

3. Plataformas de Streaming 
Las plataformas de streaming pueden usar Raje para analizar tendencias, ajustar su catálogo y 
recomendar contenido a usuarios que buscan nuevas películas y series, maximizando la 
visibilidad y engagement de su contenido.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores



### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="1">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td>
      <strong>¿Por qué llevar a cabo este análisis?</strong><br>
      Comprender cómo se posiciona Raje frente a competidores actuales en la industria de reseñas de contenido, identificando ventajas competitivas y oportunidades de diferenciación.
    </td>
  </tr>
</table>

<table>
  <thead>
    <tr>
      <th>Aspecto</th>
      <th>Raje</th>
      <th>Letterboxd</th>
      <th>Goodreads</th>
      <th>Taste.io</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="5"><strong>Perfil</strong></td>
    </tr>
    <tr>
      <td>Overview</td>
      <td>Plataforma que permite opinar libremente y sin censura sobre películas, libros y series.</td>
      <td>Red social centrada en reseñas y listas de películas.</td>
      <td>Comunidad centrada en la literatura con reseñas y ratings.</td>
      <td>Motor de recomendación de películas y series con IA.</td>
    </tr>
    <tr>
      <td>Mercado objetivo</td>
      <td>Jóvenes adultos con fuerte opinión cultural; lectores y cinéfilos activos.</td>
      <td>Cinéfilos de todas las edades que desean compartir y explorar críticas.</td>
      <td>Lectores frecuentes y amantes de los libros.</td>
      <td>Espectadores que buscan contenido afín a sus emociones o estados de ánimo.</td>
    </tr>
    <tr>
      <td colspan="5"><strong>Estrategia de marketing</strong></td>
    </tr>
    <tr>
      <td>Estrategias de marketing</td>
      <td>Libertad de expresión, alianzas con librerías y plataformas de streaming.</td>
      <td>Marketing de boca a boca y presencia en festivales de cine.</td>
      <td>Alianzas con editoriales y recomendaciones internas.</td>
      <td>Influencers, enfoque emocional, experiencia personalizada.</td>
    </tr>
    <tr>
      <td colspan="5"><strong>Producto</strong></td>
    </tr>
    <tr>
      <td>Valor ofrecido</td>
      <td>Opiniones sin censura, integración de libros, películas y series.</td>
      <td>Herramientas visuales y comunidad activa.</td>
      <td>Estadísticas de lectura y comunidad de lectores.</td>
      <td>Recomendaciones basadas en emociones y gustos.</td>
    </tr>
    <tr>
      <td>Productos y servicios</td>
      <td>Reseñas libres, rankings, perfiles personalizados, recomendaciones.</td>
      <td>Reseñas, listas, diarios de películas.</td>
      <td>Reseñas, retos de lectura, seguimiento de libros.</td>
      <td>Exploración visual, motor inteligente de recomendaciones.</td>
    </tr>
    <tr>
      <td>Precios y costos</td>
      <td>Gratuito, con posible modelo freemium.</td>
      <td>Gratuito, versión Pro con estadísticas.</td>
      <td>Gratuito.</td>
      <td>Gratuito con monetización por afiliaciones.</td>
    </tr>
    <tr>
      <td>Canales de distribución</td>
      <td>Aplicación móvil y web (en desarrollo).</td>
      <td>Web y app móvil.</td>
      <td>Web y app móvil.</td>
      <td>Web y app móvil.</td>
    </tr>
    <tr>
      <td colspan="5"><strong>Análisis SWOT</strong></td>
    </tr>
    <tr>
      <td>Fortalezas</td>
      <td>Opiniones sin filtros, integración multimedia, perfil personal.</td>
      <td>Comunidad activa, enfoque exclusivo en cine.</td>
      <td>Base de datos amplia, comunidad de lectores.</td>
      <td>IA personalizada, interfaz intuitiva.</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>Base de usuarios nueva, dependencia de alianzas.</td>
      <td>Limitado a cine.</td>
      <td>Interfaz anticuada, baja personalización.</td>
      <td>Sin comunidad visible, funciones limitadas.</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>Alianzas con librerías y plataformas, adopción por nichos.</td>
      <td>Expandirse a otros formatos como series o libros.</td>
      <td>Integrar multimedia, mejorar experiencia visual.</td>
      <td>Expansión en LATAM, personalización avanzada.</td>
    </tr>
    <tr>
      <td>Amenazas</td>
      <td>Restricciones a la libertad de expresión, competencia consolidada.</td>
      <td>Nuevas apps con más libertad o funciones.</td>
      <td>Pérdida de usuarios por falta de innovación.</td>
      <td>Competencia de algoritmos de plataformas grandes.</td>
    </tr>
  </tbody>
</table>


footoooooooo
## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
-Preguntas para consumidores de contenido multimedia 
1. ¿A menudo disfrutas de alguna serie,película o libro?
2. ¿Qué criterios utilizas al elegir qué contenido consumir?
3. ¿Sueles leer opiniones o reseñas antes de ver una película, serie o leer un libro? 
4. ¿Cómo descubres nuevas películas, series o libros? 
5. ¿Con qué frecuencia dejas opiniones o reseñas sobre el contenido que consumes? Si es 
así, ¿qué te motiva a hacerlo? 
6. ¿Usualmente usas plataformas para dejar reseñas o donde sueles dejar tu opinión? 
7. ¿Qué importancia le das a las opiniones de otros usuarios antes de elegir qué contenido 
consumir? 
8. ¿Te gustaría que las recomendaciones de películas, series o libros se ajusten más a tus 
gustos? Si es asi, como? 
9. ¿Qué aspectos no te han convencido o crees que deberían mejorarse en una plataforma 
que permite hacer reseñas sobre contenido?

-Preguntas para Dueños de Librerías
1. ¿Cómo promocionas actualmente los libros en tu librería? 
2. ¿Cómo suelen descubrir los clientes tu librería? 
3. ¿Te gustaría que existiera una plataforma donde los lectores descubran libros mediante 
reseñas de otros usuarios y como beneficiaria a tu negocio? 
4. ¿Cree que las reseñas de libros influyen en la decisión de compra de los clientes? Si es 
así ¿De qué manera? 
5. ¿Sueles recibir comentarios o recomendaciones de tus clientes? ¿Qué haces con esa 
información? 
6. Si pudieras conectar tu librería con una plataforma donde las personas descubren libros 
según sus intereses, ¿cómo te gustaría que fuera esa colaboración?

-Preguntas para Plataformas de Streaming
1. ¿Cómo deciden qué series o películas promocionar? 
2. ¿Qué aspectos consideran más importantes y útiles al promocionar una serie o película? 
3. ¿Cómo sueles enterarte de lo que más disfrutan los usuarios en tu plataforma?
4. ¿Crees que obtener los datos de una aplicación, donde los usuarios dejen reseñas y 
reciban recomendaciones personalizadas, beneficiaría a tu plataforma? 
5. ¿Cómo quisieras que los usuarios reciban sugerencias en la aplicación sobre el 
contenido de tu plataforma? 
6. ¿Cómo crees que los comentarios de los usuarios podrían ayudarte a mejorar el 
contenido que ofreces? 
7. ¿Cómo te gustaría que fuera una colaboración con una plataforma que permita a los 
usuarios encontrar nuevas películas y series según sus intereses?

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

### Epics

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EPIC-1</td>
      <td>Gestión de Cuenta</td>
      <td>Como usuario, deseo acceder a mi cuenta privada para ingresar de forma segura a la plataforma</td>
    </tr>
    <tr>
      <td>EPIC-2</td>
      <td>Personalización de Perfil</td>
      <td>Como consumidor de contenido, deseo actualizar mis intereses y gustos para recibir recomendaciones personalizadas.</td>
    </tr>
    <tr>
      <td>EPIC-3</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>EPIC-4</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>EPIC-5</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>EPIC-6</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

### User Stories

A continuación, se detallan las historias de usuario de nuestra aplicación. Cada una de ellas representa una necesidad
específica de los actores involucrados en la Plataforma, permitiendo identificar los requisitos funcionales que debe
cumplir el sistema.

Además, se incluyen los criterios de aceptación correspondientes, los cuales definen los distintos escenarios en los que
se validará cada historia de usuario. Finalmente, se indica a qué Epic pertenece cada historia, facilitando su
organización y trazabilidad dentro del desarrollo.

<table>
    <tr>
        <th>Historia de Usuario ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
    <tbody>
        <tr>
            <td>US-01</td>
            <td>Creación de Cuenta de Usuario</td>
            <td>Como usuario, deseo crear una cuenta en la plataforma para poder acceder y personalizar mi experiencia</td>
            <td>
Escenario 1:
                Dado que soy un usuario nuevo que desea registrarse en la plataforma,
                Cuando ingreso mi correo electrónico y contraseña en el formulario de registro,
                Entonces el sistema debe enviarme un correo de verificación para confirmar mi cuenta.

Escenario 2:
                Dado que tengo una cuenta en Google o Facebook,
                Cuando selecciono la opción para registrarme con estas redes sociales,
                Entonces el sistema debe permitirme crear la cuenta utilizando mis credenciales de estas plataformas. 

Escenario 3:
                Dado que el correo electrónico que intento registrar ya está en uso, 
                Cuando intento crear la cuenta,
                Entonces el sistema debe mostrarme un mensaje indicando que el correo ya está registrado y ofrecerme la opción de recuperar la contraseña.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US-02</td>
            <td>
                Inicio de Sesión
            </td>
            <td>
                Como usuario, quiero poder iniciar sesión en mi cuenta para acceder a mi perfil y gestionar mis reseñas y preferencias.
            </td>
            <td>
Escenario 1:
                Dado que tengo una cuenta registrada con mi correo electrónico y contraseña,
                Cuando ingreso mis credenciales y hago clic en "Iniciar sesión",
                Entonces el sistema debe autenticarme y llevarme a la página de inicio de mi perfil.

Escenario 2:
                Dado que he olvidado mi contraseña,
                Cuando selecciono la opción "Olvidé mi contraseña" y sigo las instrucciones,
                Entonces el sistema debe enviarme un correo electrónico para restablecer mi contraseña.

Escenario 3:
                Dado que he iniciado sesión en mi cuenta,
                Cuando hago clic en "Cerrar sesión",
                Entonces el sistema debe cerrar mi sesión y redirigirme a la página de inicio.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US-03</td>
            <td>Visualización de Opiniones y Calificaciones</td>
            <td>Como consumidor de contenido multimedia, quiero tener un perfil donde pueda ver todas mis reseñas, calificaciones y el contenido que he consumido, para poder hacer seguimiento de mis opiniones y compartirlo con otros.</td>
            <td>
Escenario 1:
Dado que he publicado varias reseñas y calificaciones en mi perfil,
Cuando accedo a la página de mi perfil,
Entonces el sistema debe mostrarme una lista de todas mis reseñas y calificaciones de contenido (películas, series, libros).

Escenario 2:
Dado que he consumido contenido recientemente,
Cuando accedo a mi perfil,
Entonces el sistema debe mostrarme un resumen de las películas, series y libros que he consumido.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-04</td>
            <td>Publicación de Reseñas y Opiniones</td>
            <td>Como consumidor de contenido multimedia, quiero poder escribir y publicar mis opiniones sobre el contenido que consumo, sin censura ni moderación, para compartir mi pensamiento de manera auténtica con otros usuarios de la comunidad.</td>
            <td>
Escenario 1:
Dado que he terminado de ver una película o leer un libro,
Cuando accedo a la opción para escribir una reseña,
Entonces el sistema debe permitirme escribir mi reseña y calificación sin que se aplique ninguna moderación ni filtro, y luego publicarla.

Escenario 2:
Dado que he publicado una reseña,
Cuando reviso mi perfil,
Entonces debo poder ver la reseña publicada junto con la calificación correspondiente.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-05</td>
            <td>Calificación de Contenido</td>
            <td>Como consumidor de contenido multimedia, quiero poder calificar las películas, series y libros que he visto o leído, para que otros usuarios puedan ver qué tan bueno o malo es el contenido según mi experiencia.</td>
            <td>
Escenario 1:
Dado que estoy viendo una película o serie,
Cuando termino de verla y decido calificarla,
Entonces el sistema debe permitir que seleccione una calificación de 1 a 5 estrellas y la publique junto con mi reseña.

Escenario 2:
Dado que ya he calificado una película o serie,
Cuando regreso a mi perfil,
Entonces debo poder ver mi calificación junto con mi reseña.

Escenario 3:
Dado que he calificado una película o serie,
Cuando decido cambiar mi calificación,
Entonces el sistema debe actualizar la calificación de acuerdo con la nueva selección.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-06</td>
            <td>Recomendaciones Personalizadas</td>
            <td>Como consumidor de contenido multimedia, quiero recibir recomendaciones personalizadas de películas, series y libros, basadas en las calificaciones y reseñas que he hecho, para descubrir nuevo contenido que se alinee con mis gustos.</td>
            <td>
Escenario 1:
Dado que he calificado varias películas, series y libros,
Cuando accedo a la sección de recomendaciones personalizadas,
Entonces el sistema debe sugerirme contenido que coincida con mis preferencias y las calificaciones previas.

Escenario 2:
Dado que las recomendaciones anteriores no me gustan,
Cuando recalifico o hago nuevas reseñas,
Entonces el sistema debe actualizar las recomendaciones según mis nuevas preferencias.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-07</td>
            <td>Seguimiento de Otros Usuarios</td>
            <td>Como consumidor de contenido multimedia, quiero poder seguir a otros usuarios cuyas opiniones me interesan, para poder ver sus reseñas y recomendaciones de manera constante en mi feed.</td>
            <td>
Escenario 1:
            Dado que estoy interesado en las opiniones de otro usuario,
            Cuando sigo a ese usuario desde su perfil,
            Entonces debo poder ver sus reseñas y recomendaciones en mi feed personal.

Escenario 2:
            Dado que ya sigo a varios usuarios,
            Cuando accedo a mi feed,
            Entonces debo ver una lista de las reseñas y recomendaciones más recientes de los usuarios que sigo.

Escenario 3:
            Dado que ya sigo a un usuario,
            Cuando decido dejar de seguirlo,
            Entonces el sistema debe dejar de mostrar sus reseñas y recomendaciones en mi feed.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-08</td>
            <td>
                Recuperación de Contraseña
            </td>
            <td>
                Como usuario, deseo poder recuperar mi contraseña en caso de olvidarla, para poder acceder nuevamente a mi cuenta.
            </td>
            <td>
Escenario 1:
Dado que he olvidado mi contraseña y hago clic en "¿Olvidaste tu contraseña?",
Cuando ingreso mi correo electrónico en el formulario de recuperación,
Entonces el sistema debe enviarme un enlace para restablecer la contraseña.

Escenario 2:
Dado que he recibido el enlace de restablecimiento de contraseña,
Cuando hago clic en el enlace y establezco una nueva contraseña,
Entonces el sistema debe confirmar que mi contraseña ha sido actualizada correctamente y redirigirme a la página de inicio de sesión.

Escenario 3:
Dado que he ingresado una nueva contraseña,
Cuando intento iniciar sesión con la nueva contraseña,
Entonces el sistema debe autenticarme correctamente y llevarme a mi página de inicio.

Escenario 4:
Dado que el correo electrónico ingresado no está registrado,
Cuando intento recuperar la contraseña,
Entonces el sistema debe mostrar un mensaje indicando que no se ha encontrado una cuenta asociada con ese correo.
            </td>
            <td>EP01</td>
        </td>
            <td>EP00</td>
        </tr>
        <tr>
            <td>US-11</td>
            <td>Ver análisis de libros mejor valorados </td>
            <td>Como dueño de librería, quiero poder ver un análisis de los libros con mejor valoración y reseñas en la plataforma, para poder hacer promociones basadas en estas valoraciones. ​</td>
            <td>Escenario 1: Acceso al top de libros valorados
Dado que soy un dueño de librería autenticado
Cuando ingreso al dashboard
Entonces veo una tabla con los 10 libros más valorados y reseñados
Escenario 2: Filtro por género
Dado que estoy en el panel de librería
Cuando selecciono el género “Mangas”
Entonces la lista se actualiza con los mejores libros valorados de ese género
Escenario 3: Filtro por género inexistente
Dado que estoy en el panel de librería
Cuando selecciono un genero inexistente
Entonces el sistema muestra un mensaje: “Genero no existente”
</td>
            <td>EP00</td>
        </tr>
        <tr>
            <td>US-12</td>
            <td>Analizar opiniones de usuarios </td>
            <td>Como administrador de plataforma de streaming, quiero analizar las opiniones de los usuarios sobre mi contenido, para ajustar mi catálogo y ofrecer mejores opciones que se alineen con sus preferencias. ​</td>
            <td>Escenario 1: Métricas generales por contenido
Dado que soy administrador de plataforma
Cuando accedo al panel de análisis
Entonces veo calificación promedio 
Escenario 2: Filtro por fecha
Dado que quiero analizar los últimos 30 días
Cuando aplico un filtro de fecha
Entonces el panel muestra solo métricas del rango indicado
Escenario 3: Filtro por género
Dado que administro contenido de múltiples géneros
Cuando selecciono “Drama”
Entonces el sistema actualiza las métricas solo con contenido etiquetado como drama
</td>
            <td>EP00</td>
        </tr>
        <tr>
            <td>US-13</td>
            <td>Ver perfil de autor o actores</td>
            <td>Como usuario, quiero poder ver la biografía y datos de un autor o actor (nombre, biografía, fecha de nacimiento, etc.), para conocer más sobre sus trabajos. ​</td>
            <td>Escenario 1: Registro exitoso
Dado que soy un nuevo usuario
Cuando completo el formulario de registro
Entonces el sistema crea mi cuenta y me redirige al perfil
Escenario 2: Inicio de sesión válido
Dado que ya tengo una cuenta
Cuando ingreso mis credenciales correctamente
Entonces accedo a mi perfil y funciones completas
Escenario 3: Error en inicio de sesión
Dado que escribo mal mi contraseña
Cuando intento iniciar sesión
Entonces el sistema muestra un mensaje de error y permite reintentar
</td>
            <td>EP00</td>
        </tr>
        <tr>
            <td>US-14</td>
            <td>Consultar elenco de película/serie </td>
            <td>Como usuario, quiero ver el listado de actores y sus roles en una película o serie, para tener contexto sobre el reparto. ​</td>
            <td>Escenario 1: Visualización básica de reparto
Dado que estoy en una ficha de serie
Cuando despliego la sección “Elenco”
Entonces aparece una lista con los actores y sus roles
Escenario 2: Acceso a perfil desde reparto
Dado que veo a un actor en el elenco
Cuando hago clic en su nombre
Entonces accedo a su perfil detallado
Escenario 3: Mostrar número de episodios
Dado que es una serie con múltiples temporadas
Cuando consulto el elenco
Entonces cada actor muestra en cuántos episodios ha participado</td>
            <td>EP00</td>
        </tr>
        <tr>
            <td>US-15</td>
            <td>Gestionar suscripciones a plataformas </td>
            <td>Como usuario, quiero vincular y desvincular mis suscripciones de streaming en mi perfil, para que la plataforma sepa dónde busco contenido. ​</td>
            <td>Escenario 1: Agregar plataforma
Dado que estoy en “Plataformas suscritas”
Cuando selecciono “Netflix” y guardo
Entonces aparece en mi lista de suscripciones y se usa para filtrar disponibilidad
Escenario 2: Eliminar plataforma
Dado que ya no uso una plataforma
Cuando la desmarco y guardo
Entonces desaparece de mi perfil y afecta mis recomendaciones
Escenario 3: Ver contenido solo en mis plataformas  
Dado que tengo varias suscripciones activas
Cuando activo el filtro “Solo mis plataformas”
Entonces solo se muestran contenidos disponibles en esas
</td>
          <td>EP00</td>
        <tr>
            <td>US-16</td>
            <td>Marcar contenido como favorito </td>
            <td>Como consumidor de contenido multimedia, quiero poder marcar una película, serie o libro como favorito, ztener un acceso rápido a mi contenido preferido. </td>
            <td>Escenario 1: Añadir a favoritos
Dado que estoy viendo una serie
Cuando pulso el ícono de estrella
Entonces se añade a mi lista de favoritos y el ícono cambia a relleno
Escenario 2: Eliminar de favoritos
Dado que un contenido ya es favorito
Cuando lo desmarco
Entonces se elimina de la lista de favoritos
Escenario 3: Visual feedback
Dado que hago clic en el icono
Cuando se registra la acción
Entonces veo una notificación “Agregado a favoritos” o “Eliminado de favoritos”

</td>
            <td>EP00</td>
        <tr>
            <td>US-17</td>
            <td>Listar mis favoritos </td>
            <td>Como consumidor de contenido multimedia, quiero ver en mi perfil una sección “Favoritos” con todas las obras que marqué, para acceder rápidamente a ellas. </td>
            <td>Escenario 1: Acceso a favoritos
Dado que tengo contenidos marcados
Cuando voy a “Favoritos” desde mi perfil
Entonces veo una lista con portadas, títulos y calificaciones
Escenario 2: Lista vacía
Dado que aún no he agregado favoritos
Cuando ingreso a la sección
Entonces el sistema muestra un mensaje motivando a marcar contenido como favorito
Escenario 3: Navegación desde favoritos
Dado que estoy en la lista
Cuando hago clic en una obra
Entonces soy redirigido a la ficha completa de ese contenido</td>
            <td>EP00</td>
        </tr>
        <tr>
            <td>US-18</td>
            <td>Feed de contenido trending </td>
            <td>Como usuario, quiero ver un feed de “Tendencias” con contenidos más reseñados y mejor valorados en la última semana, para descubrir lo más popular. </td>
            <td>Escenario 1: Cargar contenido popular
Dado que ingreso a la sección “Tendencias”
Cuando la página se carga
Entonces veo el top de contenidos más reseñados y valorados esta semana
Escenario 2: Tendencias sin reseñas
Dado que no hay reseñas recientes
Cuando accedo al feed
Entonces el sistema muestra un mensaje: “Aún no hay tendencias disponibles”
Escenario 3: Acceso desde la home
Dado que estoy en la pantalla principal
Cuando hago clic en “Ver más” bajo “Tendencias”
Entonces se abre la sección completa con más recomendaciones populares</td>
            <td>EP00</td>
        </tr>
        </tr>
        <tr>
            <td>US-19</td>
            <td>Ver trailers y portadas </td>
            <td>Como usuario, quiero ver el tráiler y la portada oficial de cada película o serie dentro de la ficha de contenido, para tener un adelanto visual antes de consumirla. </td>
            <td>Dado que estoy en la ficha de una película
Cuando cargo la sección “Multimedia”
Entonces se muestra el tráiler en un reproductor de video embebido
Escenario 2: Imagen de portada cargada correctamente
Dado que consulto la página de una serie
Cuando accedo a la sección de contenido
Entonces aparece la imagen oficial de portada en alta resolución
Escenario 3: Multimedia no disponible
Dado que el contenido no tiene tráiler cargado
Cuando accedo a la sección “Multimedia”
Entonces el sistema muestra el mensaje: “Tráiler no disponible actualmente”</td>
            <td>EP00</td>
        </tr>
        </tr>
        <tr>
            <td>US-20</td>
            <td>Marcar contenido como “Visto” </td>
            <td>Como usuario, quiero marcar manualmente una película, serie o libro como “Visto/Leído”, para mantener mi historial actualizado. ​</td>
            <td>Escenario 1: Marcar manualmente como visto
Dado que he terminado de ver una serie
Cuando entro a su ficha y pulso “Marcar como visto”
Entonces se guarda en mi historial y el botón cambia a “Visto”
Escenario 2: Evitar recomendaciones repetidas
Dado que he marcado varios contenidos como vistos
Cuando se generan nuevas recomendaciones
Entonces no incluyen contenido ya visto
Escenario 3: Desmarcar un contenido visto
Dado que marqué por error una película como vista
Cuando entro a su ficha y desactivo el estado
Entonces se elimina del historial y vuelve a estar disponible para recomendaciones
</td>
            <td>EP00</td>
        </tr>
        </tr>
        <tr>
            <td>US-21</td>
            <td>Recordar próxima fecha de estreno </td>
            <td>Como usuario, quiero recibir un recordatorio antes del estreno de una película o temporada de serie que me interesa, para agendarme con anticipación.</td>
            <td>Escenario 1: Crear recordatorio para contenido próximo
Dado que estoy en la ficha de una película próxima a estrenarse
Cuando activo “Recordarme” y selecciono un día antes
Entonces recibo una notificación por email en la fecha elegida
Escenario 2: Notificación en la app
Dado que activé un recordatorio
Cuando abro la app el día del estreno
Entonces veo una alerta dentro de la plataforma avisándome del estreno
Escenario 3: Edición o cancelación del recordatorio
Dado que ya configuré un aviso
Cuando ingreso a la configuración de recordatorios
Entonces puedo modificar la fecha o cancelar el recordatorio</td>
            <td>EP00</td>
        </tr>
        </tr>
        <tr>
            <td>US-22</td>
            <td>Bloquear usuario </td>
            <td>Como usuario, quiero bloquear a otro usuario cuyas reseñas o mensajes me resulten molestos, para no seguir viendo su actividad. ​</td>
            <td>Escenario 1: Bloquear desde perfil
Dado que estoy viendo el perfil de otro usuario
Cuando hago clic en “Bloquear” y confirmo
Entonces sus publicaciones dejan de mostrarse en mi feed y no puede escribirme
Escenario 2: Ver listado de usuarios bloqueados
Dado que he bloqueado a varios usuarios
Cuando accedo a configuración de privacidad
Entonces veo la lista completa con opción de desbloquear
Escenario 3: Intento de interacción bloqueada
Dado que un usuario está bloqueado por mí
Cuando intenta comentar una de mis reseñas
Entonces el sistema impide la acción y le muestra un mensaje: “No puedes interactuar con este usuario”
</td>
            <td>EP00</td>
        </tr>
        </tr>
        <tr>
            <td>US-23</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>
