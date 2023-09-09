# CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT
## 5.1. Software Configuration Management. 
### 5.1.1. Software Development Environment Configuration.
En nuestra startup, hemos establecido cuidadosamente la configuración de nuestro entorno de desarrollo de software para garantizar una eficiente colaboración y desarrollo de nuestras aplicaciones. Aquí están las principales herramientas y configuraciones que utilizamos:

Entornos de Desarrollo Integrados (IDEs): Utilizamos principalmente dos IDEs para el desarrollo de software. En primer lugar, Visual Studio Code, que proporciona un entorno de desarrollo altamente personalizable y esencial para nuestros desarrolladores frontend. Puedes encontrarlo en Visual Studio Code.

Herramientas de Colaboración: En cuanto a herramientas de colaboración de código, confiamos en GitHub, que es ampliamente utilizado en la comunidad de desarrollo.

Diseño de Bases de Datos y Diagramas: Para el diseño de bases de datos y la creación de diagramas diversos, utilizamos LucidChart y Vertabelo. Estas herramientas nos ayudan a visualizar y planificar nuestras estructuras de datos y flujos de trabajo.
Esta configuración de nuestro entorno de desarrollo de software es esencial para garantizar la eficiencia, la colaboración efectiva y la entrega exitosa de nuestros productos y servicios.

### 5.1.2. Source Code Management. Giakomo
Nosotros usaremos el GitHub para poder tener una mejor organización y control del desarrollo de nuestro proyecto, de la cual tiene como nombre como “AppWep-Grupo3”. En lo siguiente se adjuntara enlaces correspondiente al repositorio.

|Solución|Nombre del repositorio|Enlace|
| :-: | :-: | :-: |
|Landing Page|XComponent|https://github.com/AppWep-Grupo3/Grupo02|

[url=https://postimg.cc/87GKWHLJ][img]https://i.postimg.cc/87GKWHLJ/source.png[/img][/url]

## 5.1.3. Source Code Style Guide & Conventions. Giakomo
En nuestra startup, establecemos rigurosas convenciones y estándares de desarrollo para garantizar un proceso de desarrollo coherente y eficiente. A continuación, detallamos nuestras prácticas y directrices:

Convenciones de Nomenclatura: Para mantener una uniformidad en el código, seguimos las convenciones básicas de camelCase y UpperCamelCase según corresponda. Además, tomamos como referencia la guía de estilo de Google para programar en HTML y CSS (Google HTML/CSS Style Guide) para asegurar una estructura clara y legible en nuestros archivos HTML y CSS.

Control de versiones: Para el control de versiones, aplicamos el enfoque de conventional commits tanto en la creación de ramas como en la realización de commits. Por ejemplo:

Rama: feat/main-component
Commit: feat(ui): agregado el template del componente principal
Gestión de Ramas: Utilizamos el modelo de GitFlow para la creación de ramas. Esto significa que seguimos una estructura de ramas que incluye características (feature branches) y correcciones (hotfixes), todas basadas en nuestra rama principal, que es la rama "main". Esta rama principal contiene la versión de la aplicación en producción y se actualiza mediante la integración con Cloudflare Pages, lo que garantiza despliegues automáticos y eficientes.

Estas prácticas y directrices son fundamentales para mantener un código limpio, coherente y bien gestionado a medida que desarrollamos nuestras aplicaciones y servicios. Además, nos ayudan a mantener una trazabilidad clara de las actualizaciones y mejoras en nuestro proyecto.

### 5.1.4. Software Deployment Configuration. Giakomo
Para tener una óptima visualización de la elaboración de nuestro Landing Page usamos la opción de GitHub llamado GitHub Page para así mostrar cada commit del Landing Page ya desplegado:
1. Una vez que todas las ramas estén actualizadas, se procede a ingresar a Github, luego acceder al repositorio del proyecto y seguidamente dar clic en “Settings”:

[![deployment.png](https://i.postimg.cc/8C41XnsC/deployment.png)](https://postimg.cc/WDDLh8GR)

2. Una vez dentro de Settings, buscar la opción “Pages” en el  menú lateral:

[![deployment1.png](https://i.postimg.cc/hjg67S0y/deployment1.png)](https://postimg.cc/Jy6PfCvZ)

3. Seleccionar la rama principal, luego dar clic en “Save”, y GitHub comenzara el proceso de deploy:

[![deployment2.png](https://i.postimg.cc/W3nKGQW2/deployment2.png)](https://postimg.cc/47YBZFRM)

4. Una vez que todo el proceso de deploy haya terminado, se mostrara al inicio un mensaje de confirmación junto con el link del Landing Page desplegado:

[![deployment3.png](https://i.postimg.cc/wTbCbY6M/deployment3.png)](https://postimg.cc/KRBpRV3h)

5. Finalmente, se podrá acceder a la pagina desde el enlace que se generó anteriormente:

[![deployment4.png](https://i.postimg.cc/mr7KDc71/deployment4.png)](https://postimg.cc/wtTw4jf9)

Enlace de nuestro Landing Page: https://appwep-grupo3.github.io/Grupo02/ 

## 5.2. Landing Page, Services & Applications Implementation. 
### 5.2.1. Sprint 1
### 5.2.1.1. Sprint Planning 1. 

| **Sprint #**           | Sprint 1                                       |
| ---------------------- | --------------------------------------------- |
| **Sprint Planning Background**                                  |
| Date                   | 05/09/2023                                      |
| Time                   | 22:30 horas                                     |
| Location               | Virtual meeting - Google meet                   |
| Prepared By            | Anthony Avalos                                  |
| **Attendees (to planning meeting)** | Anthony Avalos Santos, Alexis Vargas Quispe, Giakomo, Javier Sebastian, Mariela |
| **Sprint n-1 Review Summary**   | (No hubo sprint anterior)                     |
| **Sprint n-1 Retrospective Summary** | (No hubo sprint anterior)                |
| **Sprint Goal & User Stories**                                |
| Sprint 1 Goal          | Landing Page XComponents                       |
| Sprint 1 Velocity      | Dadas las condiciones de ser el primer sprint, el velocity establecido será 30. |
| Sum of Story Points    | Para el presente Sprint se decidió un total de 22 Story Points. |

### 5.2.1.2.	Sprint backlog 1

                                                                                |                                
| Id   | Title           | Id   | Títle                            | Description                                          |Estimatiin (Hours) |  Assigned To     |  Status (To do/InProcess/ToReview/Done)  |
| ---- | ---------------- | ---- | --------------------------------- | --------------------------------------------------- | ------------------- | ---------------- | --------- |
| SS01 | Sección header   | WT01 | Implementación de la sección header, navbar y los estilos. | Desarrollar la barra de navegación con estilos CSS y JS | 3                   | Anthony Avalos   | Done      |
| SS02 | Sección servicios | WT02 | Implementación de la sección de servicios | Desarrollar la sección de servicios con estilos responsive | 2                   | Alexis Vargas    | Done      |
| SS03 | Sección planes   | WT03 | Implementación de la sección planes | Desarrollo e implementación de los planes con estilos | 2                   | Javier Sebastian | Done      |
| SS04 | Sección equipo   | WT04 | Implementación de la sección “Conócenos” | Desarrollo e implementación de los perfiles del equipo de desarrollo | 4                   | Giakomo          | Done      |
| SS05 | Sección detalles | WT05 | Implementación de la sección detalles | Implementar correctamente los detalles y estilos responsive | 4                   | Mariela Martinez | Done      |



### 5.2.1.3.	Development evidence for sprint review

| Repository                                         | Branch         | Commit Id  | Commit Message          | Commit Message Body  | Commited on (Date) |
|---------------------------------------------------|----------------|------------|-------------------------|----------------------|--------------------|
| [https://github.com/AppWep-Grupo3/Grupo02](https://github.com/AppWep-Grupo3/Grupo02) | Feature/Anthony | 7c08546    | Feat: header            | -                    | 06/09/2023         |
|                                                   | Feature/Alexis  | 30c5513    | Feat: Sección Servicios | -                    | 06/09/2023         |
|                                                   | Feature/Mariela | b7e6e2d    | Feat: Seccion detalles  | -                    | 06/09/2023         |
|                                                   | Feature/Javier  | ab865a5    | Feat: Sección planes    | -                    | 06/09/2023         |
|                                                   | Feature/Giako   | 6ª7e147    | Feat: Seccion equipo    | -                    | 06/09/2023         |

### 5.2.1.4.	Testing suite evidence for sprint review
En esta entrega, no se incluyó esta sección, ya que se enfocó principalmente en el desarrollo del Landing Page como base del proyecto. Ya que se logró desarrollar el Sprint 1 satisfactoriamente, nuestro landing page posee implementadas las user stories especificadas en nuestro Sprint Backlog

### 5.2.1.5.	Execution evidence for sprint review

[![prototipo.png](https://i.postimg.cc/xTj8W189/prototipo.png)](https://postimg.cc/9zSc9Vyk)

Enlace del video: https://www.youtube.com/watch?v=cL_LQ4DQaLM

### 5.2.1.6.	Services documentation evidence for sprint review
Para este primer Sprint no fue contemplada la documentación de nuestros servicios, ya que se enfocó principalmente en la creación del Landing Page.

### 5.2.1.7.	Software deployment evidence for sprint review
Despliegue, en github pages maybe
Para llevar a cabo la correcta implementación y despliegue de nuestro Landing Page, se utilizó la herramienta Github Pages. Esta plataforma permite generar sitios web directamente desde donde se encuentre el repositorio público que contiene el código que se utilizó para crear la página. 
A Continuación, se indicará el enlace de nuestro Landing PAge: https://appwep-grupo3.github.io/Grupo02/

### 5.2.1.8.	Team collaboration insights during sprint
Para este primer Sprint, se utilizó herramientas como Github, y Visual Code para llevar a cabo todos los commits necesarios. Uno de nuestros miembros realizó el primer commit que viene a ser la creación del repositorio. Posteriormente se clonó el repositorio para trabajar localmente en VsCode. Se crearon las ramas correspondientes para cada modificación realizada. A Continuación, se pueden evidenciar los commits hechos:

[![commit.png](https://i.postimg.cc/J4Rf4wc7/commit.png)](https://postimg.cc/w3bf0GGn)

# CONCLUSIONES

### Conclusiones y recomendaciones
- Una de las conclusiones que podemos rescatar es que la correcta identificación de nuestro segmento objetivo fue de gran ayuda para enfocarnos principalmente en darle una experiencia satisfactoria al usar nuestro servicio.

- Dada la tecnología needfinding, fue posible determinar las necesidades y deseos de los usuarios. De este modo, se desarrolla una aplicación web que satisface los requerimientos del usuario.

- Este informe ha proporcionado una visión detallada de lo que será nuestra aplicación para comprar componentes y/o periféricos y que den como parte de pago un producto usado que será con un fin benéfico.

- El desarrollo del Landing Page fue de mucha ayuda para que los usuarios puedan conocer mucha más sobre nuestro startup y de la finalidad de nuestra aplicación, si como también de las funcionalidades que tiene, y que además, esa página muestra el equipo de desarrollo, quienes tomaron esta gran iniciativa para contribuir a la educación de los estudiantes.


- La creación de un prototipo de alta fidelidad no permite ver la aplicación en su totalidad desde una perspectiva de un usuario consumidor, que además nos ayudó a mejorar. También, nos permitió recolectar comentarios de los usuarios entrevistados para poder realizar los cambios necesarios y ofrecer una mejor experiencia para los usuarios.


# Video About-the-Team

Link:https://youtu.be/6SEKvJFTB6E




# BIBLIOGRAFÍA

Espinoza, O, et.al (2011). Diagnóstico del Manejo de los Residuos Electrónicos en el Perú. Recuperado de: https://www.cooperacionsuiza.pe/wp-content/uploads/2011/04/diagnostico-raee.pdf  [Consulta: 27/08/2023]

Ministerio del Ambiente. (2017). Gestion responsable de los RAEE. Recuperado de: https://www.facebook.com/MinamPeru/posts/10156008189124973/ [Consulta: 27/08/2023]

Sustainable Cycles (SCTCLE) Programme. (2020).  The Global E-waste Monitor 2020- Quantitiesm flows, and the circular economy potential. Recuperado de: https://ewastemonitor.info/gem-2020/ [Consulta: 27/08/2023]




