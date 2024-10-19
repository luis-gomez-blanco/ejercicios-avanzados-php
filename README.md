# EJERCICIOS AVANZADOS DE PHP

1. Mejora el ejercicio de conversión de divisas propuesto en *Ejercicios básicos de PHP* mediante una página que muestre 4 divisas diferentes en dos desplegables y un campo numérico. Será obligatorio para enviar el formulario que el campo numérico tenga algún valor numérico. La página del resultado muestra la conversión del campo numérico de la primera divisa a la segunda. Se deben emplear los controles HTML adecuados en cada caso, pudiendo validar la entrada mediante código JavaScript, que deberá ir en un archivo externo.

2. Crear un programa en PHP que, implementando distintos estilos que provienen de un archivo externo CSS, permita elegir mediante dos desplegable el color de fondo de la página y el color de la fuente. Se incluirán también dos casillas de selección donde indicar la decoración, negrita y/o cursiva, de la tipografía. Al enviar el formulario se cargará la misma página, aplicando los cambios de estilo. Las opciones seleccionadas por el usuario deben mantenerse en el formulario tras la carga de la página.
3.
4. decorarse 
5.
6. Crear un único archivo PHP con ciertas clases en un CSS. Se ha de dar a elegir mediante un desplegable el
color de fondo, y con otro, el color de la letra. Mediante dos checkbox se ha de dar la opción de indicar si
la fuente es además cursiva o negrita. Si se envía el formulario se carga la misma página con el cambio de
estilo. Por último, las opciones elegidas han de recordarse cuando se recargue la página. Ha de usar un
archivo externo de CSS.


BASES DE DATOS

Desarrollo de Aplicaciones Multiplataforma

Desarrollo de Aplicaciones Web

# ÍNDICE

[Introducción	1](#_toc180153927)

[Resultados de aprendizaje	1](#_toc180153928)

[Proceso de enseñanza	2](#_toc180153929)

[Estrategia didáctica	2](#_toc180153930)

[Metodología	2](#_toc180153931)

[Instrumentos de evaluación	3](#_toc180153932)

[Periodo ordinario	3](#_toc180153933)

[Evaluación ordinaria	4](#_toc180153934)

[Evaluación extraordinaria	4](#_toc180153935)

[Procedimiento de evaluación	5](#_toc180153936)

[Recuperación	5](#_toc180153937)

[Pérdida de evaluación continua	5](#_toc180153938)

[Medidas de refuerzo durante el periodo extraordinario	6](#_toc180153939)

[Criterios de calificación	6](#_toc180153940)

[Calificación final	7](#_toc180153941)

[Normas del aula	7](#_toc180153942)

[Bibliografía recomendada	9](#_toc180153943)





*v1.0 - 18/10/2024**

# <a name="_toc180153927"></a>Introducción
El profesor de la asignatura de *Bases de datos* quiere daros la bienvenida a todos los alumnos al nuevo curso escolar *2024/25*. Afrontaremos este nuevo año con ilusión y espero que con el esfuerzo de todos se consigan unos excelentes resultados y logros en vosotros, buscando potenciar en cada uno lo mejor de sí mismo, tanto en el plano académico como en el personal y humano.

Para que todo funcione correctamente, considero que es fundamental la colaboración y comunicación, por lo que me pongo a vuestra disposición para cualquier cuestión que podáis necesitar. Las comunicaciones se realizarán preferentemente de forma directa con el profesor o, excepcionalmente, por correo electrónico o teléfono. Os recuerdo que mi correo electrónico es: <luis.gomezblanco@educa.madrid.org>

Es fundamental que los alumnos tomen conciencia de la importancia del esfuerzo, del trabajo bien hecho y de la honestidad, así como del valor de ser artífices de su propio aprendizaje y, por ello, este documento pasa a ser un contrato de trabajo entre alumno y profesor, a través del cual se detalla la manera en que se espera que funcionen ambos.

# <a name="_toc180153928"></a>Resultados de aprendizaje
La siguiente lista de resultados de aprendizaje (en adelante RA) se ha confeccionado a partir de los decretos legislativos vigentes en materia educativa de aplicación a este ciclo formativo:

1. *Reconoce los elementos de las bases de datos analizando sus funciones y valorando la utilidad de los sistemas gestores.*
1. *Crea bases de datos definiendo su estructura y las características de sus elementos según el modelo relacional.*
1. *Consulta la información almacenada en una base de datos empleando asistentes, herramientas gráficas y el lenguaje de manipulación de datos.*
1. *Modifica la información almacenada en la base de datos utilizando asistentes, herramientas gráficas y el lenguaje de manipulación de datos.*
1. *Desarrolla procedimientos almacenados evaluando y utilizando las sentencias del lenguaje incorporado en el sistema gestor de bases de datos.*
1. *Diseña modelos relacionales normalizados interpretando diagramas entidad/relación.*
1. *Gestiona la información almacenada en bases de datos objeto-relacionales, evaluando y utilizando las posibilidades que proporciona el sistema gestor.*

Su consecución se llevará a cabo bajo el contexto de las posibilidades tecnológicas disponibles en el centro y buscando el mayor grado posible de aprendizaje significativo basado en la filosofía de “aprender haciendo”.

Además de los resultados de aprendizaje indicados, se espera que el alumno desarrolle habilidades como:

- El trabajo regular y la constancia.
- El aprendizaje por sí mismo (autonomía responsable) y con los demás (trabajo en equipo).
- La capacidad de razonamiento lógico identificando las soluciones más convenientes de entre las posibles.
- La selección y priorización de la información manejada.
- La producción y presentación profesional de la información requerida.
- El dominio de herramientas de comunicación avanzadas.

# <a name="_toc180153929"></a>Proceso de enseñanza
## <a name="_toc180153930"></a>Estrategia didáctica
Considerando que alumno no ha tenido anteriormente contacto con el módulo de *Bases de datos*, el siguiente itinerario de aprendizaje que se presenta busca en todo momento dos objetivos principales:

1. El aterrizaje gradual en cada nuevo bloque de conocimiento.
1. La adquisición más significativa posible de las habilidades básicas para el diseño y la programación de bases de datos.

Para ello se ha diseñado un sistema de aprendizaje que se nutre de:

- Explicaciones del profesor.
- Materiales elaborados por el profesor: presentaciones gráficas, pruebas de autoevaluación, ejercicios propuestos y ejercicios resueltos, proyectos, etc.
- Libro de apoyo de la asignatura.

Los materiales estarán reunidos en un aula virtual donde se localizarán los recursos necesarios para abordar los aprendizajes del módulo.

Cualquier conocimiento contenido en los recursos colgados en esta aula virtual, será susceptible de ser preguntado en cualquiera de los cuestionarios. De ahí que una manera correcta de afrontar el aprendizaje en este módulo comienza con la lectura de los enlaces y documentos colgados en el bloque del aula virtual que se esté trabajando en cada momento.

Resulta de gran ayuda completar los ejercicios de autoevaluación, para consolidar los conocimientos adquiridos a través de las explicaciones y la lectura de los temas. Asimismo, se deben probar el mayor número de ejercicios resueltos e intercalar su solución de alguno de los propuestos.

*Por último, debe quedar claro al alumno que este módulo se coordina con el de Entornos de Desarrollo, como si de una extensión del mismo se tratara y se relaciona asimismo con el de Programación.*
## <a name="_toc180153931"></a>Metodología
Los aspectos metodológicos que se aplicarán en este módulo se basan en la idea de que el alumno se considere parte activa de la actividad docente.

El objetivo es involucrarlo en el proceso de asimilación de conceptos y adquisición de capacidades, no como mero contenedor de ellos, sino como productor directo de los mismos.

La impartición del módulo se fundamentará en los siguientes aspectos:

- El estudio de cada unidad de trabajo se inicia con la exposición de los contenidos, impartidos por el profesor.

- Posteriormente, se llevarán a cabo una serie de ejercicios propuestos por el docente con el objetivo de llevar a la práctica los conceptos teóricos que se impartieron en la exposición.

- El profesor resolverá las dudas que puedan plantearse, tanto teóricas como prácticas. Incluso, si lo considerase necesario, se realizarán ejercicios específicos de refuerzo que aclaren los conceptos que más cueste comprender a los alumnos.

- Más adelante, el profesor propondrá un conjunto de ejercicios y casos prácticos, de contenido similar a los que ya se han resuelto en clase, que deberán ser resueltos por los alumnos, bien en horas de clase o bien en casa.

- Las prácticas se resolverán de forma individual o en grupo, dependiendo del número de alumnos que haya por cada ordenador. En cualquier caso, no es aconsejable que haya más de dos alumnos por cada equipo informático.

- Se proporcionará a los alumnos documentación sobre los conceptos fundamentales, cuando se crea conveniente. Se citarán libros de consulta y portales de Internet adecuados para las distintas unidades de trabajo.
## <a name="_toc180153932"></a>Instrumentos de evaluación
<a name="_hlk180148664"></a>El conjunto de instrumentos de evaluación que se emplearán en este módulo es el siguiente:
### <a name="_toc180153933"></a>Periodo ordinario

|<a name="_hlk180148707"></a>**Nombre**|Actividad|
| :-: | - |
|**Objetivo**|Su finalidad es propiciar que el alumno realice ejercicios clave necesarios, de forma que adquiera los mínimos conocimientos y entrenamiento cerebral que permita el trabajo en contenidos posteriores.|
|**Tipología**|Comentarios de texto, trabajos de investigación documental, trabajos expositivos, resolución de ejercicios, desarrollo de código, etc.|

Los condicionantes de este instrumento son los siguientes:

- La no presentación de una actividad, por causa no debidamente justificada a criterio del profesor, implicará que el mismo lo califique con un cero en todos sus apartados.

- La no presentación de una actividad, por causa debidamente justificada a criterio del profesor y comunicada previamente (si ello es posible), implicará que el mismo establezca un nuevo periodo para su realización y nueva fecha de presentación acordada por ambas partes, siempre que sea posible.

|**Nombre**|Prueba de evaluación|
| :-: | - |
|**Objetivo**|Su propósito es medir el grado de seguimiento y asimilación de los conceptos trabajados por parte del alumno, así como de la regularidad de repaso de estos.|
|**Tipología**|Preguntas, ejercicios, desarrollo de código, etc.|

Los condicionantes de este instrumento son los siguientes:

- En caso de no presentarse el alumno a la realización de la prueba, por causa no debidamente justificada a criterio del profesor, el mismo lo calificará con un cero, sin posibilidad de nueva realización.

- En caso de no presentarse el alumno a la realización de la prueba, por causa debidamente justificada a criterio del profesor y comunicada previamente (si ello es posible), y no hubiera opción a su repetición, el mismo la calificará tomando como nota la obtenida en la prueba instrumental correspondiente a los criterios de evaluación asociados al RA.


|<a name="_hlk180152765"></a>**Nombre**|Prueba instrumental|
| :-: | - |
|**Objetivo**|La realización permitirá evaluar el grado de adquisición de cada competencia del módulo.|
|**Tipología**|Preguntas, ejercicios, desarrollo de código, etc.|

Los condicionantes de este instrumento son los siguientes:

- En el caso de no presentación del alumno a la prueba, por causa no debidamente justificada a criterio del profesor, el mismo la calificará con un cero.

- En el caso de no presentación del alumno a la prueba, por causa debidamente justificada a criterio del profesor, el mismo procederá a su repetición en un plazo establecido por él.
### <a name="_hlk180152809"></a><a name="_toc180153934"></a>Evaluación ordinaria

|**Nombre**|Prueba instrumental|
| :-: | - |
|**Objetivo**|La realización permitirá evaluar el grado de adquisición de cada competencia del módulo.|
|**Tipología**|Preguntas, ejercicios, desarrollo de código, etc.|

Los condicionantes de este instrumento son los siguientes:

- En el caso de no presentación del alumno a la prueba, por causa no debidamente justificada, se calificará con un cero.

- En el caso de no presentación del alumno a la prueba, por causa debidamente justificada, implicará que se establezca una nueva fecha para su realización, siempre que sea posible.
### <a name="_toc180153935"></a>Evaluación extraordinaria

|**Nombre**|Prueba instrumental|
| :-: | - |
|**Objetivo**|La realización permitirá evaluar el grado de adquisición de cada competencia del módulo.|
|**Tipología**|Preguntas, ejercicios, desarrollo de código, etc.|

Los condicionantes de este instrumento son los siguientes:

- En el caso de no presentación del alumno a la prueba, por causa no debidamente justificada, se calificará con un cero.

- En el caso de no presentación del alumno a la prueba, por causa debidamente justificada, implicará que se establezca una nueva fecha para su realización, siempre que sea posible.
## <a name="_toc180153936"></a>Procedimiento de evaluación
Siguiendo el procedimiento de evaluación continua, durante el periodo ordinario se plantearán diversas actividades y/o pruebas de evaluación que permitirán medir el grado de adquisición de cada competencia indicada en los RA a través de sus criterios de evaluación. Si la calificación de un RA resultara negativa, esto es, inferior a 5, el alumno deberá volver a evaluarse de los contenidos asociados a dicho RA en la prueba instrumental. Si la calificación en dicha prueba volviera a ser negativa, el alumno deberá evaluarse de los contenidos asociados a dicho RA en la prueba ordinaria.

Ante la posible demanda de que algún alumno le plantee al profesor un procedimiento que le permita mejorar su calificación, la respuesta inicial es rotundamente “no”. El argumento se fundamenta en que el diseño evaluativo realizado por el profesor persigue mantener un nivel alto de trabajo durante los trimestres, permitiendo al alumno un control responsable de su rendimiento. Salvo que concurran circunstancias de índole personal o familiar que impidan el normal desarrollo del trabajo durante uno o varios trimestres y la buena trayectoria previa del alumno se viera empañada por ello, el profesor denegará esta posibilidad.

Si en la prueba ordinaria la calificación de un RA resultara negativa, esto es, inferior a 5, el alumno deberá volver a evaluarse de los contenidos asociados a dicho RA en la evaluación extraordinaria.

Si en la prueba extraordinaria la calificación de un RA resultara negativa, esto es, inferior a 5, no se hará media con el resto de RA para el cálculo de la nota final, y se suspenderá el módulo.
## <a name="_toc180153937"></a>Recuperación
De acuerdo con lo expuesto anteriormente, no se establece un sistema de recuperación ni por CE ni por RA. Si terminado el periodo ordinario de evaluación el alumno no hubiera superado alguno de los RA asociados al módulo, deberá examinarse de aquellos en la prueba ordinaria que se celebra.
## <a name="_toc180153938"></a>Pérdida de evaluación continua
Para aquellos alumnos que acumulen faltas de asistencia, justificadas o sin justificar que superen el 20% de las horas totales del módulo, perderán el derecho a evaluación continua y su nota será cero en todos los RA. En este caso, el alumno será evaluado solamente en las pruebas ordinaria y extraordinaria a final de curso.

Si un alumno pierde el derecho a evaluación continua podrá seguir asistiendo a clase si así lo desea, pero el profesor no tendrá obligación de corregirle ningún examen o trabajo, que, en cualquier caso, dejarán de ser evaluables.

En todo caso, la activación del protocolo de pérdida de evaluación continua queda a criterio del docente, analizando pormenorizadamente cada situación personal del alumno.
## <a name="_evaluación_ordinaria"></a><a name="_toc180153939"></a>Medidas de refuerzo durante el periodo extraordinario
El alumno debe comprender que cuando accede al periodo extraordinario, el tiempo es tan reducido que se requiere por su parte, más que nunca, un compromiso de asistencia y dedicación máximos.

Bajo estas circunstancias el profesor resolverá las dudas puntuales planteadas por los alumnos, tanto a nivel teórico como práctico, sobre los contenidos expuestos en el módulo a lo largo del curso, pudiendo plantear de manera personalizada unos ejercicios acordes a superar la evaluación final, en función de las carencias detectadas en cada alumno.

# <a name="_toc180153940"></a>Criterios de calificación
La naturaleza de este módulo es eminentemente procedimental, por lo que primará este aspecto tanto a la hora desarrollar los instrumentos como en la carga evaluativa de éstos. 

Aunque **Bases de Datos** requiere de un profundo estudio conceptual, sin estos el desarrollo práctico se dificultaría innecesariamente, no consiguiendo el nivel que los resultados de aprendizaje persiguen. No obstante, conviene dejar claro, de cara a su procedimiento de calificación, una serie de advertencias previas de carácter general:

- <a name="_hlk180153081"></a>Si en la lectura que realice el profesor de los trabajos presentados por los alumnos se detectase fehacientemente (buscadores, detectores de plagios o similares) el más mínimo proceso de copia de algún documento de Internet, enciclopedia, revista o cualquier medio de comunicación similar o compañero, la evaluación de dicho trabajo se considerará cero para todos los alumnos implicados.

- Cuando en la revisión de cualquier trabajo existieran sospechas del uso de asistentes digitales o de inteligencias artificiales, el profesor podrá requerir al alumno, sin previo aviso, para que explique su respuesta donde, las incongruencias y/o faltas de justificación y/o ausencias de criterio en su desarrollo, provocarán que sea calificado con un cero en todos los apartados.

- Cualquier alumno que sea sorprendido copiando, hablando o con cualquier tipo de anotación, así como con cualquier código o documento del curso sin importar su autoría, que no hayan sido previamente autorizados por el profesor, y con independencia de que se le haya visto usándolos durante la realización de una prueba objetiva, será calificado con un cero en dicha prueba, pudiendo recuperar según las normas establecidas para ello. Esta eventualidad incluye el uso de asistentes digitales e inteligencias artificiales de cualquier tipo.

- <a name="_hlk180153182"></a>Si el profesor tuviera sospechas de que alguna prueba ha sido copiada, repetirá la prueba al alumno por escrito u oralmente sin previo aviso para así constatar si, efectivamente, el alumno ha adquirido las competencias asociadas. Si el resultado no fuera satisfactorio, se considerará que ha habido copia y el alumno será calificado con un cero. Del mismo modo, si hubiera sospechas del uso de algún tipo de asistente digital o inteligencia artificial en el desarrollo de la prueba, el profesor podrá requerir al alumno, sin previo aviso, para que explique su respuesta donde, las incongruencias y/o faltas de justificación y/o ausencias de criterio en su desarrollo, provocarán que sea calificado con un cero en todos los apartados.

- Asimismo, se recuerda que, según normativa de la Comunidad de Madrid, está prohibida la utilización de móviles o cualquier otro dispositivo electrónico en todas las instalaciones del centro, y durante toda la jornada escolar salvo autorización expresa del profesor para actividades concretas. Especialmente grave es el uso de este tipo de dispositivos para copiar o comunicarse con otros alumnos o con personas situadas fuera de las instalaciones. Debido a la gravedad y transgresión de normas de rango superior a las del propio centro, se informa que cualquier alumno que sea sorprendido usando un dispositivo electrónico para cualquier finalidad durante la realización de una prueba objetiva suspenderá automáticamente la evaluación correspondiente, debiendo recuperarla en las pruebas correspondientes. Para evitar este tipo de situaciones, los alumnos no deben traer dichos dispositivos al centro y, de hacerlo, deberán permanecer apagados en sus mochilas, nunca en bolsillos, estuches, cajoneras o similares. De incumplirse este punto, no se atenderá ningún tipo de justificación para la presencia de estos dispositivos.

- Por último, cabe advertir que las notas parciales quedarán siempre supeditadas a que el alumno no pierda el derecho a evaluación continua, en cuyo caso, la nota de todos los RA será cero y se le evaluará solamente mediante las pruebas ordinaria y extraordinaria de final de curso.

Por ello y, para evitar situaciones poco agradables para todos y que pueden perjudicar el rendimiento general de la clase, se ruega que cada alumno sea consciente de la importancia de asumir las consecuencias de sus propios actos, en caso de no cumplirlas.
### <a name="_hlk180153251"></a><a name="_toc180153941"></a>Calificación final
La calificación final, según se indica en la legislación vigente, se orientará hacia la consecución de los RA planteados en el módulo, que contrastados con las necesidades actuales de las empresas y en relación con los distintos criterios de evaluación asociados a aquellos, se obtendrá a partir de la media ponderada de todos los RA según se indica:

|**Resultado de aprendizaje**|**Ponderación**|
| :-: | :-: |
|RA1|5 %|
|RA2|5 %|
|RA3|25 %|
|RA4|15 %|
|RA5|15 %|
|RA6|25 %|
|RA7|10 %|
|**Total:**|**100%**|

# <a name="_toc180153942"></a>Normas del aula
Para el correcto desarrollo de las clases se establecen las siguientes normas, cuyo objetivo es lograr un buen clima en el aula, manteniendo el respeto al profesor y al resto de compañeros:

- La asistencia a clase y la puntualidad son fundamentales para el correcto desarrollo de las sesiones. Se contabilizará como retraso llegar tarde hasta 10 minutos en la primera hora y 5 minutos en las siguientes. Si se superan 10 minutos de la primera hora o 5 de las restantes, se contabilizará como falta. Asimismo, la suma de 2 retrasos injustificados computará como una falta para el control de horas totales de pérdida de evaluación continua y pérdida de matrícula. Se ruega que se justifiquen por escrito cuanto antes las faltas de asistencia.

- Los alumnos deberán esperar al profesor dentro del aula y ya sentados en los sitios que se les hayan asignado. En el caso de tener que desplazarse a otra dependencia deberá hacerlo con la máxima diligencia y rapidez y portando los materiales necesarios.

- Para la realización de las actividades de aula, los alumnos deberán asistir con los siguientes materiales:
  - Un medio de almacenamiento extraíble propio.
  - Opcionalmente, su propio equipo portátil, aunque será el propio alumno el responsable del uso apropiado y de posibles daños o robo.
  - Libro de texto según las indicaciones del profesor.
  - Papel y medios de escritura.
  - Aquellos materiales complementarios que el profesor solicite para la realización de actividades concretas.

- Durante el curso, profesor observará e insistirá a alumnos (o equipos, si así se planteara), en los siguientes aspectos:
  - El grado de consecución de los ejercicios o pruebas propuestos.
  - La corrección a la hora de formalizar sus soluciones.
  - La corrección en el manejo de las herramientas.
  - La capacidad de enfrentar los problemas por sí mismo e integrado en un equipo de trabajo.
  - La regularidad de realización en clase y en casa de los trabajos y/o ejercicios propuestos.
  - La puntualidad en la entrega de los anteriores.
  - La correcta expresión oral en público.
  - La intensidad del trabajo desarrollado.
  - La asistencia a clase.
  - La participación en clase (las iniciativas y aportaciones didácticas, las preguntas durante la explicación, el apoyo y resolución de dudas de los compañeros, etc.)  y en el aula virtual (las aportaciones didácticas, las preguntas y la resolución de dudas en el tablón, la aportación a glosarios, etc.)
  - La penalización en la calificación de medio punto si aparecen entre cinco y nueve faltas de ortografía y con un punto si sobrepasa las nueve faltas en una prueba escrita o documentación presentada.

Estos y demás indicadores de interés del alumno por la materia podrán modular la nota final de la evaluación al alza, como máximo, un punto.

- Durante el curso se priorizará la entrega de materiales y la recogida de tareas escritas a través de la plataforma **Google Classroom**, para minimizar el intercambio de materiales entre los profesores y los alumnos. Es fundamental que los alumnos se familiaricen con su uso cuanto antes.

- Se recuerda la importancia de devolver firmados en los plazos establecidos todos los documentos que se entreguen para su firma, como notas informativas o partes de amonestación.

# <a name="_toc180153943"></a><a name="_hlk180153706"></a>Bibliografía recomendada
Para el seguimiento de la asignatura será necesario la toma activa de apuntes en clase, ya que las presentaciones expuestas por el profesor constituyen la base de estudio del módulo. Asimismo, se recomienda el apoyo del alumno en las siguientes fuentes bibliográficas.

- Bibliografía básica:
  - Lerma Blasco, R., Murcia Andrés, J., Chamorro Molina, J., & Oltra Landete, F. (01 de 09 de 2021). Bases de datos. Libro digital interactivo. Madrid: McGraw Hill. Obtenido de FP McGraw Hill.

- Bibliografía complementaria:
- Mora Roja, A. (2014). Bases de datos. Diseño y gestión. Madrid: Síntesis.

2

