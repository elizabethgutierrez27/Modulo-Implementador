# Modulo-Implementador
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
Requisitos.
  

<!-- Descripción -->
#### Descripción.
El proyecto estaba planeado para ser trabajado en un período de 4 meses, durante los cuales los integrantes de los equipos se encargarían de desarrollar un módulo cada uno, de manera que todos contribuyeran con una parte del mismo y se fuera desarrollando de forma que todos los equipos trabajaran al mismo ritmo.

<!-- Objetivos -->
#### Objetivos.
Los objetivos se trabajaron simultáneamente, centrándose principalmente en el trabajo en equipo y la capacidad de adaptación de los integrantes de los equipos para trabajar en un módulo asignado por el encargado. En total, participaron 4 equipos que se dividieron en grupos de 5 a 6 personas para desarrollar cada módulo. En cada equipo, había un líder encargado de dirigir y asignar las tareas a los integrantes del equipo.

<!-- Organigrama -->
#### Organigrama.
![2](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/142765604/3388243b-1151-429f-bf5b-3cb222759956)
![Pink Colorful Modern Organizational Chart Graph](https://github.com/elizabethgutierrez27/Modulo-Implementador/assets/142765604/8d1d5e4d-77d8-4a33-99ed-889c52313f57)

<!-- Diagrama Gantt -->
#### Diagrama Gantt.


<!-- Análisis del proyecto -->
## Análisis de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Requerimientos -->
#### Requerimientos.
- <b>Formato tipo checklist para seleccionar historias:</b>
  - <b>Descripción:</b> Como implementador, necesito un formato de checklist para seleccionar las historias de usuario que deseo liberar, con el fin de facilitar la gestión y liberación de nuevas funcionalidades en el sistema.
  - <b>Criterios de Aceptación:</b>
      - Debe existir un formato de checklist bien visible y accesible para el implementador.
      - El proceso de marcar y desmarcar historias en el checklist debe ser claro y fácil de usar.
  
- <b>Visualizar historias finalizadas y su fecha de agenda:</b>
  - <b>Descripción:</b> Como implementador, necesito poder visualizar todas las historias con estado "Finalizado" y ver la fecha en que fueron agendadas, para tener un registro claro de las tareas completadas y su programación.
  - <b>Criterios de Aceptación:</b>
    - La aplicación debe mostrar todas las historias con estado "Finalizado" de manera clara y organizada.
    - La fecha de agenda de cada historia finalizada debe ser visible y estar asociada a la historia correspondiente.

- <b>Aplicar filtros para agrupar historias por fecha y sistema:</b>
  - <b>Descripción:</b> Como implementador, necesito poder aplicar filtros para agrupar las historias por fecha según el sistema, con el objetivo de organizar y visualizar las tareas de manera más eficiente y contextualizada.
  - <b>Criterios de Aceptación:</b>
    - La aplicación debe tener un botón de filtro bien visible y accesible.
    - Al aplicar un filtro, las historias deben agruparse según las categorías definidas en el sistema, como fecha y sistema, de manera rápida y precisa.

- <b>Visualizar y gestionar historias por sistema o pantalla:</b>
  - <b>Descripción:</b> Como implementador, necesito una pantalla que muestre las etiquetas de sistemas o pantallas, y al seleccionar una de ellas, ver un listado de historias asociadas, con la opción de agendarlas o rechazarlas.
  - <b>Criterios de Aceptación:</b>
    - La pantalla debe presentar claramente las etiquetas de sistemas o pantallas.
    - Al seleccionar una etiqueta, debe mostrarse un listado de historias asociadas de manera clara y organizada.
    - Debe haber opciones para agendar o rechazar las historias de usuario desde esta pantalla.

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

<!-- Arquitectura MVC y Middleware -->
#### Arquitectura.
Del lado del cliente se encuentra:

- ASPX
    - Aqui es donde se realiza el codif¿go en html
    - Es llamado en este modulo como sistema.aspx
      
- JS
    - Es donde se tiene la iteracion directa con el aspx
    - Aqui es donde se encuentran todas las funciones, en este caso estas fueron:
        - mostrarTabla(): Esta se utilizo para hacer ma muestra de las etiquetas clasificadas por ("agendadas", "no agendadas" y "liberadas")
        - obtenerDatosTablaAgendadas(): Este es para mostrar y traer los datos de la base de datos de aquellas que no estan agendadas las historias de usuario
        - obtenerDatosTablaSinAgendar(): Este es para traer y mostrar los datos de la tabla sin agendar de la base de datos
        - obtenerDatosTablaLiberadas(): Este fue usado para taer la informacion y mostrarla de las historias que ya estan liberadas, esto se refleja cuando se ejecuta el procedimineto almacenado.
        - formatearFecha(fecha): Este es para dar un formato de fecha "dd/mm/yyyy"
          
Estos dos de comunican mediante el jquery

Del lado del servidor se encuentra:
- ASPX.CS
    - Aqui se tiene el codigo de los metodos base del proyecto.
    - En este caso se llama sistema.aspx.cs
    - ObtenerHistoriasAgendadas()
    - ObtenerHistoriasNoAgendadas()
    - ObtenerHistoriasLiberadas()
     - ObtenerSistemas()
- Cs
  - Aqui se tiene las clases, y el codigo c#.      

  Esta parte se comunica mediante el ajax, con el se conecta.

<!-- Código Fuente -->
#### Código Fuente.
Código Fuente de la solución


<!-- Pruebas proyecto -->
## Pruebas.
En las pruebas para la corroboración de la funcionalidad del módulo implementador se realizaron los casos de prueba, en donde se describen detalladamente cada caso de prueba, incluyendo la entrada, los pasos a seguir y los resultados esperados. De igual manera se agrega un informe de las pruebas que es donde se resumen los resultados de las pruebas, incluyendo estadísticas, resultados de casos de prueba individuales y observaciones sobre el rendimiento del sistema. Y con ello se agregan la documentación donde se hace evidencia de la ejecución de pruebas y los resultados obtenidos, especialmente útil para problemas relacionados con la interfaz de usuario.

<!-- Casos de prueba -->
#### Casos de prueba.
https://docs.google.com/spreadsheets/d/1n4uHmXCagVOX4vX-S-bOL7Pf4TK6VPiIetmMg_U13g4/edit?usp=drivesdk

<!-- Ejecución Casos de prueba -->
#### Ejecución.
Evidencia de Ejecución de Casos de prueba.
https://docs.google.com/document/d/1NciyJqEn-g1AlpSxKmyVL93LuK40g6JaVpsiHJQszMw/edit?usp=sharing

<!-- Iniciando -->
## Iniciando

<!-- Requisitos -->
### Requisitos
Requisitos de Instalación.

<!-- Instalación -->
### Instalacion
Se hace uso de varias herramientas de software para poder trabajar con el proyecto proporcionado, por ello se hizo más de una instalación.
- Instalar Visual Studio 2022 en caso de no tenerlo
- Tener activo el servidor con el uso de la VPN
- Para la VPN tener el programa FortiClient
- Descragar el proyecto, y ejecutarlo desde el Visual Studio


## Guias
https://docs.google.com/document/d/13suY7d1wHpf0kEZPHYaeZFLQgEIiGsEzgZvhL_BoiX0/edit?usp=sharing

## contribucion
Contribucion.

## Licencia
Licencia.

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


