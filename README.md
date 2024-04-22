![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/124726616/5f3a9148-2f51-443c-bdb1-eeb2e057d74b)# Modulo-Implementador
# Integradora II

## contenido
<details>
  <summary>Tabla contenidos</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del Proyecto</a>
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#objetivos">Objetivos</a></li>
        <li><a href="#organigrama">Organigrama</a></li>
        <li><a href="#diagrama-gantt">Diagrama Gantt</a></li>
      </ul>
    </li>
    <li>
      <a href="#análisis-de-la-solución">Análisis de la Solución</a>
      <ul>
        <li><a href="#requerimientos">Requerimientos</a></li>
        <li><a href="#diagrama-casos-de-uso">Diagrama de Casos de Uso</a></li>
      </ul>
    </li>
    <li>
      <a href="#diseño-de-la-solución">Diseño de la Solución</a>
      <ul>
        <li><a href="#modelo-relacional">Modelo Relacional</a></li>
        <li><a href="#diagrama-de-clases">Diagrama de Clases</a></li>
        <li><a href="#diagrama-de-componentes">Diagrama de Componentes</a></li>
      </ul>
    </li>    
    <li>
      <a href="#implementación">Implementación</a>
      <ul>
        <li><a href="#estándares-codificación">Estándares Codificación</a></li>
        <li><a href="#arquitectura">Arquitectura</a></li>
        <li><a href="#código-fuente">Código Fuente</a></li>
      </ul>
    </li>      
    <li>
      <a href="#pruebas">Pruebas</a>
      <ul>
        <li><a href="#casos-de-prueba">Casos de prueba</a></li>
        <li><a href="#ejecución">Ejecución</a></li>
      </ul>
    </li>       
    <li><a href="#guias">Guias</a></li>
    <li><a href="#contribucion">Contribución</a></li>
    <li><a href="#licencia">licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
## Acerca del proyecto
Claro, aquí tienes un resumen de los requisitos basado en los requerimientos proporcionados:

El proyecto "Implementador" requiere la implementación de varias funcionalidades clave para facilitar la gestión y liberación de nuevas funcionalidades en el sistema. Entre estos requisitos se incluyen la accesiblilidad para seleccionar historias de usuario a liberar, la visualización de historias finalizadas junto con sus fechas de agenda para un registro claro de tareas completadas, la capacidad de aplicar filtros para agrupar historias por fecha y sistema para una organización eficiente, y una pantalla dedicada para visualizar y gestionar historias por sistema o pantalla, incluyendo opciones para agendar o rechazar las historias seleccionadas. Estos requisitos son fundamentales para garantizar la eficiencia y la claridad en el proceso de gestión de historias de usuario en el sistema "Implementador".
  

<!-- Descripción -->
#### Descripción.
- <b>Período de Tiempo:</b> El proyecto se llevó a cabo desde el 8 de enero al 15 de abril de 2024. Durante este tiempo, el equipo trabajó en el desarrollo del módulo asignado (Modulo de implementador).

- <b>Metodología:</b> Se utilizó la metodología ágil Scrum para gestionar el proyecto, permitiendo trabajar en sprints y hacer ajustes conforme a los resultados y retroalimentación obtenidos.

- <b>Riesgos:</b> Durante el desarrollo del proyecto, surgieron problemas relacionados con la gestión del tiempo y la comprensión del código. Estos desafíos impactaron en el avance del trabajo, pero fueron abordados con sesiones de revisión y comunicación continua.

- <b>Equipo:</b>
Inicialmente, el equipo estaba compuesto por cinco integrantes:
            Oscar Ramírez: Líder del proyecto y Analista de datos, responsable de supervisar y coordinar el trabajo del equipo, gestionar y desarrollar la implementacion de la base de datos.
            Elizabeth Olvera: Desarrolladora de software, encargada de codificar partes específicas del módulo.
            Alejandro Rangel: Desarrollador de software, encargado de verificar la funcionalidad del módulo, ademas de apoyar con los estilos del modulo.
            Manuel Mata y Mildret Banda: Desarrolladores de software que abandonaron el proyecto poco después del inicio.
        Posteriormente, dos nuevos miembros se unieron para reforzar el equipo:
            Noah Torres: Desarrollador de software, quien asumió parte de las tareas de codificación y posteriormente el liderazgo del equipo.
            Josué Núñez: Diseñador de interfaces, encargado de mejorar la experiencia del usuario en el módulo.

- <b>Interesados del Proyecto:</b> Los interesados principales en el proyecto eran los departamentos de desarrollo y tecnología, así como los usuarios finales del módulo.


<!-- Objetivos -->
#### Objetivos.
El objetivo del módulo fue desarrollar una funcionalidad integral para observar, gestionar y organizar historias en el sistema. El módulo permite a los usuarios clasificar las historias en estatus, como sin agendar, agendadas y liberadas, además de agendar y liberar historias según sea necesario. Esto tiene como finalidad optimizar la gestión y el seguimiento de las historias, proporcionando una mejor organización y control en el sistema para mejorar la toma de decisiones y la eficiencia operativa.

<!-- Organigrama -->
#### Organigrama.
![2](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/142765604/3388243b-1151-429f-bf5b-3cb222759956)
![Pink Colorful Modern Organizational Chart Graph](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/142765604/8d1d5e4d-77d8-4a33-99ed-889c52313f57)

<!-- Diagrama Gantt -->
#### Diagrama Gantt.
https://drive.google.com/file/d/1ig-yxv5Z7F41PLMByc46e3o4rQ-RD2xW/view?usp=drive_link

<!-- Análisis del proyecto -->
## Análisis de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Requerimientos -->
#### Requerimientos.
## Requerimientos

| Requerimiento                                                                                                          | Descripción                                                                                             | Criterios de Aceptación                                                                                |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| **Formato tipo checklist para seleccionar historias**                                                                   | Como implementador, necesito un formato de checklist para seleccionar las historias de usuario que deseo liberar, con el fin de facilitar la gestión y liberación de nuevas funcionalidades en el sistema. | - Debe existir un formato de checklist bien visible y accesible para el implementador. <br> - El proceso de marcar y desmarcar historias en el checklist debe ser claro y fácil de usar.|
| **Visualizar historias finalizadas y su fecha de agenda**                                                              | Como implementador, necesito poder visualizar todas las historias con estado "Finalizado" y ver la fecha en que fueron agendadas, para tener un registro claro de las tareas completadas y su programación. | - La aplicación debe mostrar todas las historias con estado "Finalizado" de manera clara y organizada. <br> - La fecha de agenda de cada historia finalizada debe ser visible y estar asociada a la historia correspondiente.|
| **Aplicar filtros para agrupar historias por fecha y sistema**                                                         | Como implementador, necesito poder aplicar filtros para agrupar las historias por fecha según el sistema, con el objetivo de organizar y visualizar las tareas de manera más eficiente y contextualizada. | - La aplicación debe tener un botón de filtro bien visible y accesible. <br> - Al aplicar un filtro, las historias deben agruparse según las categorías definidas en el sistema, como fecha y sistema, de manera rápida y precisa.|
| **Visualizar y gestionar historias por sistema o pantalla**                                                            | Como implementador, necesito una pantalla que muestre las etiquetas de sistemas o pantallas, y al seleccionar una de ellas, ver un listado de historias asociadas, con la opción de agendarlas o rechazarlas. | - La pantalla debe presentar claramente las etiquetas de sistemas o pantallas. <br> - Al seleccionar una etiqueta, debe mostrarse un listado de historias asociadas de manera clara y organizada. <br> - Debe haber opciones para agendar o rechazar las historias de usuario desde esta pantalla. |


<!-- Diagrama de Casos de Uso -->
#### Diagrama Casos de Uso.
![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/47889de3-afe2-429f-9afc-e93821ffa36b)


<!-- Diseño del proyecto -->
## Diseño de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Modelo Relacional -->
#### Modelo Relacional.
Se hace uso de las mismas tablas que el modulo de Historias Terminadas
![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/158323858/a54b06ab-2ba9-4bab-9465-c3abd97cb44a)


<!-- Diagrama de Clases -->
#### Diagrama de Clases.
![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/09223050-af42-4c47-a10b-00f5b79cd6d0)


<!-- Diagrama de Componentes -->
#### Diagrama de Componentes.
![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/09b8bc56-eb8c-4c2c-842b-e7a2ef538853)

### Diagrama de actividades
![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/e5eb59fb-8cb5-4b24-be3d-dfd8eed263be)

<!-- Implementación del proyecto -->
## Implementación.
Los principales elementos incluidos en la implementación son:
- <b>Código Fuente:</b> Se proporciona el código fuente de la aplicación, organizado según las convenciones de estructura de proyecto y nomenclatura acordadas. (En una carpeta con el nombre del modulo, dentro el archivo aspx, aspx.cs y el js)
- <b>Documentación Técnica:</b> Se incluye documentación detallada sobre la arquitectura de la aplicación, los componentes utilizados, los patrones de diseño empleados y las decisiones de implementación importantes.
- <b>Pruebas: </b>Se describen las pruebas realizadas durante el desarrollo, incluyendo pruebas unitarias, de integración, y pruebas de aceptación del usuario. Se pueden proporcionar resultados de pruebas y registros de errores.
- <b>Recursos Desplegados:</b> Se enumeran los recursos desplegados en el entorno de producción,la base de datos ocupada que en este caso fue llamada DBSGICE_ERP.

#### Estándares Codificación.
En el desarrollo del proyecto se siguieron los estándares de codificación recomendados por la empresa Nad Global y la buena práctica:
- <b>Convención de nomenclatura:</b>
    - Los identificadores deben comenzar con una letra o un carácter de subrayado (_).
    - Se usa PascalCase para nombres de tipo, espacios de nombres y todos los miembros públicos.
    - Elegir nombres de ensamblado que representen el propósito principal del ensamblado.
    - Utilizar camelCase para los parámetros de los métodos y las variables locales.
- <b>Comentarios y documentación: </b> Se incluyeron comentarios descriptivos en el código para explicar su funcionamiento y propósito

- Estándares de Codificación SQL
  - En el desarrollo del proyecto, se siguieron los estándares de codificación recomendados por la empresa Nad Global y las buenas prácticas en SQL:

  - Convención de nomenclatura:
    - Se utilizó CamelCase para los nombres de tablas y columnas. Por ejemplo, NombreTabla y NombreColumna.
    - Se prefirió el uso de minúsculas para palabras compuestas. Por ejemplo, nombreTabla en lugar de NombreTabla.
    - Se evitó el uso de espacios o caracteres especiales en los nombres de tablas y columnas para facilitar la escritura de consultas SQL.
  - Estructura del código:
    - Se mantuvo una estructura coherente y legible en las consultas SQL, utilizando sangrías y espacios en blanco de manera consistente.
    - Se dividió el código SQL en bloques lógicos utilizando comentarios descriptivos para mejorar la legibilidad y el mantenimiento.

<!-- Arquitectura MVC y Middleware -->
#### Arquitectura.
Del lado del cliente se encuentra:

- ASPX
    - Aqui es donde se realiza el código en html
    - Es llamado en este módulo como sistema.aspx
      
- JS
    - Es donde se tiene la iteración directa con el aspx
    - Aqui es donde se encuentran todas las funciones, en este caso estas fueron:
        - mostrarTabla(): Esta se utilizó para hacer ma muestra de las etiquetas clasificadas por ("agendadas", "no agendadas" y "liberadas")
        - obtenerDatosTablaAgendadas(): Este es para mostrar y traer los datos de la base de datos de aquellas que no estan agendadas las historias de usuario
        - obtenerDatosTablaSinAgendar(): Este es para traer y mostrar los datos de la tabla sin agendar de la base de datos
        - obtenerDatosTablaLiberadas(): Este fue usado para taer la información y mostrarla de las historias que ya estan liberadas, esto se refleja cuando se ejecuta el procedimineto almacenado.
        - formatearFecha(fecha): Este es para dar un formato de fecha "dd/mm/yyyy"
          
Estos dos de comunican mediante el jquery

Del lado del servidor se encuentra:
- ASPX.CS
    - Aqui se tiene el código de los métodos base del proyecto.
    - En este caso se llama sistema.aspx.cs
    - ObtenerHistoriasAgendadas()
    - ObtenerHistoriasNoAgendadas()
    - ObtenerHistoriasLiberadas()
     - ObtenerSistemas()
- Cs
  - Aqui se tiene las clases, y el código c#.      

  Esta parte se comunica mediante el ajax, con el se conecta.

<!-- Código Fuente -->
#### Código Fuente.
Por razones de seguridad y protección, no se proporciona el código fuente en esta sección. El código fuente de la aplicación ha sido deliberadamente omitido y no está disponible para su visualización pública.


<!-- Pruebas proyecto -->
## Pruebas.
En las pruebas para la corroboración de la funcionalidad del módulo implementador se realizaron los casos de prueba, en donde se describen detalladamente cada caso de prueba, incluyendo la entrada, los pasos a seguir y los resultados esperados. De igual manera se agrega un informe de las pruebas que es donde se resumen los resultados de las pruebas, incluyendo estadísticas, resultados de casos de prueba individuales y observaciones sobre el rendimiento del sistema. Y con ello se agregan la documentación donde se hace evidencia de la ejecución de pruebas y los resultados obtenidos, especialmente útil para problemas relacionados con la interfaz de usuario.

<!-- Casos de prueba -->
#### Casos de prueba.
https://docs.google.com/spreadsheets/d/1n4uHmXCagVOX4vX-S-bOL7Pf4TK6VPiIetmMg_U13g4/edit?usp=drivesdk

<!-- Ejecución Casos de prueba -->
#### Ejecución.
Evidencia de Ejecución de Casos de prueba.
[https://docs.google.com/document/d/1NciyJqEn-g1AlpSxKmyVL93LuK40g6JaVpsiHJQszMw/edit?usp=sharing](https://docs.google.com/document/d/1T0ipbvW1YWnb8pQBYZTPRFHQaiwXjbksTOqmbJ0Pk3E/edit)

<!-- Iniciando -->
## Iniciando

<!-- Requisitos -->
### Requisitos
- Instalar Tortoise versión 1.14.6
- Instalar Visual Studio 2022. 
- Instalar Framework ASP.NET.
- Instalar SQL Server Management Studio 19
- Instalar FortiClient versión 7.2.3.
- Descargar complemento SSL de FortiClient.


<!-- Instalación -->
### Instalacion
Se hace uso de varias herramientas de software para poder trabajar con el proyecto proporcionado, por ello se hizo más de una instalación.
Para iniciar el proyecto, seguimos los siguientes pasos para permitir que cada miembro del equipo pueda trabajar en él en sus propias estaciones de trabajo.

- Iniciamos el programa de Tortoise para descargar el proyecto.

- Para obtener el proyecto en nuestra estación de trabajo, accedemos al software de Tortoise y proporcionamos la URL donde está almacenado el proyecto. Luego, procedemos a descargarlo.

- Para acceder a la base de datos, ejecutamos el software SQL y utilizamos las credenciales proporcionadas por la empresa.

- Iniciamos FortiClient e ingresamos las credenciales de usuario también proporcionadas por la empresa.

- Una vez que la conexión VPN está activa, lanzamos Visual Studio 2022 y abrimos nuestro proyecto desde la sección "Abrir". Posteriormente, lo ejecutamos como un sitio web.


## Guias
https://docs.google.com/document/d/13suY7d1wHpf0kEZPHYaeZFLQgEIiGsEzgZvhL_BoiX0/edit?usp=sharing

## Pantallas
Principal:
![Imagen de WhatsApp 2024-04-14 a las 21 57 59_cc29f4ca](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/c722b04b-ff5b-47c9-8ccb-6befff2b7ef7)

Agendadas:
![Imagen de WhatsApp 2024-04-14 a las 21 57 58_1578f4c2](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/529638a5-6b20-42c2-9fc7-b88580ef69c2)

Sin agendar:
![Imagen de WhatsApp 2024-04-14 a las 21 57 59_a1e6d8e3](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/146129308/72eca2f5-53c3-43cb-ade4-b926e41ae088)


Liberadas:
![image](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/158323858/3ab1c658-6e76-4b60-a4de-7fc8ca0ac5db)



## Contacto
- nunezomar294@gmail.com
- atnoah666@gmail.com
- alejandrollamas2000@gmail.com
- uli.ses140511@gmail.com
- elizabethgolvera@gmail.com

## Participantes
- Arredondo Torres Noah Noel
- Gutierrez Olvera Elizabeth
- Nuñez Godinez Josue Omar
- Ramirez Cruz Oscar Ulises
- Rangel Perez Alejandro


