# [Sitio de Nuevas Tecnologías FIUBA](http://nuevas-tecnologias-fiuba.github.com)

Este repositorio contiene el sitio de github de la materia. Pueden colaborar de la forma que quieran, ya sea creando issues, o agregando/modificando el contenido.

## Clases

* [Scala](https://github.com/Nuevas-Tecnologias-FIUBA/Clase-Scala)
* [Groovy](https://github.com/Nuevas-Tecnologias-FIUBA/Clase-Groovy/)
* [Grails](https://github.com/Nuevas-Tecnologias-FIUBA/Clase-Grails/)



# Materias
## Seminario de Ingeniería Informática I (75-71)
## Seminario de Ingeniería Informática II (75-72)
## Desarrollos con Nuevas Tecnologías (95-68)

### Año 2018 - 1° cuatrimestre

## Régimen de la materia


## Objetivo

Que los alumnos puedan construir aplicaciones con nuevas herramientas de
desarrollo de software, validando nuevas teorías, que les permitan
generar innovaciones tecnológicas para satisfacer requerimientos que
deben cumplir los nuevos productos de software.

## Motivación

El cambio tecnológico en las tecnologías de información y comunicaciones
es vertiginoso. Con la instalación del paradigma centrado en red, que
surge a partir de Internet, este medio se ha convertido en un poderoso
ambiente habilitador de muchas innovaciones tecnológicas. Lo interesante
en el ámbito del desarrollo de software es que muchas de las tecnologías
que aparecen se caracterizan como “software libre”, es decir, que
permiten no solamente utilizarlo, sino que también se puede mejorar y
compartir tales mejoras con la comunidad. Esto brinda oportunidades para
el desarrollo de innovaciones tecnológicas que podrían utilizarse en
cualquier lugar del mundo.

En el ámbito académico de una Facultad de Ingeniería es importante
conocer estas nuevas tecnologías y aprovechar las “ventanas de
oportunidad” que aparecen en un escenario tan cambiante, para que, a
partir de algunas de las herramientas que se pueden bajar gratuitamente
de Internet, se puedan construir aplicaciones que se adapten a este
nuevo paradigma planteado.

## Tecnologías habilitadas para el desarrollo

### Herramientas (software de base)

El punto de partida desde el punto de vista de las herramientas a
utilizar es la “Plataforma Java”, entendiendo como tal al lenguaje de
Programación Java con su especificación JSE (Java Standard Edition), que
incluye las APIs (Application Programming Interfaces, es decir las
bibliotecas de clases básicas que provee el lenguaje) y su máquina
virtual , la “Java Virtual Machine”. Dado que muchas de las aplicaciones
que se desarrollan están en un ambiente de empresas, se incluye también
elementos de JEE (Java Enterprise Edition).

Esta plataforma habilita el uso de muchas herramientas construidas sobre
ella, como es el caso de los contenedores livianos (como es el caso del
Framework Spring y todos los proyectos asociados al mismo, que cubren
con creces los requerimientos de herramientas de desarrollo de nuevas
aplicaciones). También en la plataforma Java han aparecido nuevos
lenguajes que corren sobre su máquina virtual (Scala y Groovy, entre
otros), que proveen facilidades para el desarrollo de aplicaciones que
siguen el paradigma funcional, permitiendo la exploración de soluciones
de software que trasciendan el paradigma dominante de objetos y puedan
resolver de manera elegante algunos problemas que la orientación a
objetos no resuelve satisfactoriamente. Además, estos nuevos lenguajes
facilitan la creación de “lenguajes específicos de dominio” (DSL, Domain
Specific Languages) , lo que permite con relativa facilidad generar un
lenguaje de programación de pequeña complejidad que soporte conceptos
del dominio de aplicación (es decir el problema a resolver específico)
que se quiere implementar.

Por otro lado, la irrupción de las bases de datos NOSQL (Not Only SQL)
plantean nuevos desafíos para la persistencia de los datos en memoria de
disco (y posiblemente en las nuevas memorias masivas), por lo que es un
tema a tratar entre los ítems más relevantes de las nuevas tendencias
que están apareciendo en la actualidad.

### Conceptos Principales

La cátedra entiende que el punto de partida para el desarrollo de
aplicaciones avanzadas es un buen diseño de su arquitectura y de sus
conceptos principales. Para ello se basa esencialmente en los conceptos
del diseño del dominio de la aplicación que se quiere modelar (Domain
Driven Design). Por eso, es importante manejar técnicas que permitan
conocer, a partir de los requerimientos que debe cumplir una aplicación
(las “historias de usuario” o “casos de uso”), cuáles son los conceptos
más fuertes (abstracciones) que aparecen en los problemas a resolver
(aplicaciones a desarrollar), de modo tal que, con la ayuda de un
lenguaje orientado a objetos como Java (o cualquiera de los nuevos
lenguajes citados anteriormente) se puedan crear clases que satisfagan
tales requerimientos y permitan integrarse a los frameworks existentes,
sin tener dependencias con los mismos.

Requisitos para la aprobación
-----------------------------

Para aprobar la materia se debe presentar y aprobar un trabajo práctico,
cuyo tema será de elección del alumno o grupo de alumnos que realizarán
el trabajo, previo acuerdo con el equipo docente, dando preferencia al
desarrollo en
[*Groovy*](http://en.wikipedia.org/wiki/Groovy_(programming_language)) y
[*Grails*](http://en.wikipedia.org/wiki/Grails_(framework)) de una
aplicación de tipo empresarial que integre tecnologías y conceptos
innovadores. El alcance será definido por el equipo docente en función
de la cantidad de integrantes del grupo, que podrá ser de a lo sumo de
cuatro participantes.

### Entrega Parcial

Se debe realizar una entrega previa, **que tiene las características de
examen parcial**, 
que consiste en:

- Un texto breve que describe en grandes rasgos el dominio sobre el cual se trabaja,

- Una serie de historias de usuario -cuyo número dependerá de la cantidad de integrantes del grupo-

- Un modelo de dominio que dé soporte a las historias escritas.

- Un sistema funcionando, preferentemente escrito en grails.

Como ejemplo de los dos primeros puntos, se adjuntan los enunciados de
los Anexos, “Issue Tracker” y “Sitio de Subastas”, junto con sus
correspondientes historias de usuario. El modelo de dominio debería
estar implementado en JavaSE (Java Standard Edition) o en Scala o
Groovy, usando los conceptos de orientación a objetos aprendidos en
Algoritmos III y los explicados en las clases sobre Domain-Driven
Design, de forma tal que a partir de la lectura del código sean
evidentes los conceptos y funcionalidades involucrados. Técnicamente, el
dominio del problema debe estar modelado con lo que se conoce como
“POJOs” (Plain Old Java Objects) (o POSOs o POGOs).

La entrega final consiste en la presentación de una aplicación en donde
se implementen totalmente las historias de usuario. Para esto es
necesario integrar una serie de tecnologías y frameworks que brinden la
infraestructura adecuada al modelo del dominio. Se sugiere la
utilización del Framework Spring para resolver la inyección de
dependencias e Hibernate para resolver la persistencia. Esto está
facilitado con el uso del framework Grails y del lenguaje Groovy.

El trabajo práctico se presentará en alguna fecha de coloquio
habilitada. Para su aprobación, además de las preguntas acerca de lo
realizado en el trabajo práctico, se podrán hacer preguntas sobre los
temas conceptuales explicados en clase, especialmente los que tiene que
ver con “Domain Driven Design”. En el trabajo práctico final se prestará
especial atención a que el modelo de dominio NO tenga las
características de un “modelo de dominio anémico” (concepto que se
explicará oportunamente).

### Entrega Final

#### Objetivo

Mostrar un prototipo funcional de aplicación que implemente los casos de
éxito de las historias de usuario presentadas en la entrega parcial y
acordadas con el equipo docente, haciendo uso de los conceptos, técnicas
y tecnologías explicados durante el desarrollo de la cursada.

#### Alcance

Como mínimo, cada una de las historias de usuario presentadas en la
entrega parcial y acordadas con el equipo docente debe resultar
funcional. No es necesario contemplar validaciones obvias o historias de
usuario triviales, pero sí las historias secundarias relacionadas con
las reglas del negocio que se está tratando. No se trata de desarrollar
un sistema completo en cada una de sus características, sino un
prototipo funcional de algunos aspectos centrales. De esta forma, debe
calcularse el alcance teniendo en cuenta que debería poder ser
desarrollado a lo largo de un cuatrimestre.**

#### Restricciones

Los lenguajes, plataformas y herramientas utilizados en el desarrollo
deben ser de \[código abierto\]([*http://en.wikipedia.org/wiki/Open-source\_software*](http://en.wikipedia.org/wiki/Open-source_software)) \

#### Entrega

La presentación del trabajo práctico final consiste en una exposición
oral que cuente con una introducción al tema (diapositivas, tiza y
pizarrón u oral) y una demostración del funcionamiento de la aplicación,
siguiendo cada historia de usuario desde la interfaz de usuario hasta el
mecanismo de persistencia, explicando tecnologías usadas, problemas y
soluciones encontrados, arquitectura propuesta, modularización usada,
descomposición funcional del trabajo. En particular se hará hincapié en
la distancia usada en el lenguaje del espacio de la solución y el usado
en el espacio del problema. Esto es: qué tan cercanos son la redacción
de las historias de usuario y la del código fuente que las implementa.

Los alumnos que cursan la materia 95-68, “Desarrollo con Nuevas
Tecnologías” deberán responder además preguntas teóricas sobre los temas
tratados en clase.

<table>
<tr>
<td>
En síntesis, debe quedar en claro que la materia trabaja sobre dos líneas: la primera, que tiene que ver con modelos de dominio de sistemas (en especial de gestión) plasmados en código escrito con buenas prácticas de diseño con tecnología de orientación a objetos en Java (o los nuevos lenguajes), sin infraestructura. La segunda parte tiene que ver con la infraestructura necesaria para que la aplicación escale adecuadamente, favoreciendo la utilización de tecnologías innovadoras.

Como punto final, se destaca el compromiso de la cátedra con el “software libre”:  existen excelentes productos de software libre que se pueden bajar libremente por Internet, cuyas licencias permiten utilizarlo, ver su código fuente, mejorarlo e incluso publicarlo, sin que se violen derechos de propiedad intelectual. Por eso todos los trabajos prácticos se realizarán con software libre.
</td>
</tr>
</table>

Criterios de evaluación final
-----------------------------

### Sobre el modelo elegido

-   Definición del contexto y modelo del dominio

-   Implementación funcional basada en el modelo

-   Adherencia a los POJOs (POSOs, POGOs)

### Sobre la implementación

<!-- -->

-   Explicación de las decisiones de arquitectura y diseño

-   Nivel de expresividad del código fuente

-   Capacidad de construcción de un lenguaje basado en el modelo

-   Integridad conceptual de la implementación

-   Manejo de los conceptos explicados en clase

-   Explicación de los problemas encontrados

-   Justificación de las tecnologías utilizadas

## Cuerpo Docente

Profesor: Lic Pablo G. Cosso     [*pablo.cosso@gmail.com*](mailto:pablo.cosso@gmail.com?subject=Desarrollo%20con%20Nuevas%20Tecnologías)

Ayudante: Lic. Marcos Saladino   [*marcos.saladino@gmail.com*](mailto:marcos.saladino@gmail.com?subject=Desarrollo%20con%20Nuevas%20Tecnologías)

Ing. Mauro Ciancio               [*maurociancio@gmail.com*](mailto:maurociancio@gmail.com?subject=Desarrollo%20con%20Nuevas%20Tecnologías)

### Amigos
Ing. Nicolás Bello Camilletti    [*nbellocamilletti@gmail.com*](mailto:nbellocamilletti@gmail.com?subject=Desarrollo%20con%20Nuevas%20Tecnologías)

Lic. Flavio Oliveri              [*flavio.oliveri@gmail.com*](mailto:flavio.oliveri@gmail.com?subject=Desarrollo%20con%20Nuevas%20Tecnologías)


## Lista de correo electrónico de la materia

La materia cuenta con un lista de correo electrónico en google:

[*http://groups.google.com/group/nuevas-tecnologias-fiuba*](http://groups.google.com/group/nuevas-tecnologias-fiuba)
----------------------------------------------------------------------------------------------------------------------

## Github

La materia posee una cuenta en github

[*https://github.com/Nuevas-Tecnologias-FIUBA*](https://github.com/Nuevas-Tecnologias-FIUBA)
  ----------------------------------------------------------------------------------------------

## Sitios de Interés

**Java**     [*http://www.oracle.com/technetwork/java/index.html*](http://www.oracle.com/technetwork/java/index.html)

**Scala**    [*http://www.scala-lang.org/*](http://www.scala-lang.org/)

**Groovy**   [*http://groovy-lang.org/*](http://groovy-lang.org/)

**Spring**   [*http://www.springsource.org/*](http://www.springsource.org/)

**Grails**   [*http://grails.org/*](http://grails.org/)

## Anexo A: Issue Tracker

### Escenario

Registración y edición de historias de usuario

La historia está escrita en formato BDD, Behavior Driven Development
([*http://en.wikipedia.org/wiki/Behavior-driven\_development*](http://en.wikipedia.org/wiki/Behavior-driven_development))
, que se puede utilizar para cumplir con los requerimientos de un
desarrollo en Grails. Se incluye además un Gráfico con un modelo de
clases básico para el ejemplo. Este modelo es anémico, por lo que se
recomienda analizar qué significa ese concepto y cómo se puede mejorar
(si es posible). El segundo gráfico muestra un comportamiento modelado
como transición de estados, que puede ayudar al objetivo de mejora.

### Historias de Usuario

*Como* desarrollador, *quiero* registrar una serie de historias de
usuario en un backlog *para* organizar el trabajo y saber cuáles quedan
por hacer, cuáles están en proceso, cuáles hay que verificar y cuáles
están hechas.\
\
Escenario: tipo de historia.\
*Dado* que quiero identificar de qué tipo es cada historia, cuando cargo
o edito una, *entonces* tengo que poder registrar si se trata de una
nueva funcionalidad, un defecto, un trabajo técnico o una adquisición de
conocimientos.\
\
Escenario: temas.\
*Dado* que quiero agruparlas por tema, *cuando* cargo o edito una una,
*entonces* tengo que poder asignarles un tema.\
\
Escenario: puntos.*\
Dado* que quiero tener una idea estimada de *cando* voy a tenerlas todas
resueltas, cuando cargo o edito una, *entonces* tengo que poder
asignarles 1, 3, 5, 8 ó 13 puntos de historia.\
\
Escenario: asignados.*\
Dado* que quiero poder delegar una historia, *cuando* cargo o edito una,
*entonces* tengo que poder registrar quién la tiene asignada.\
\
Escenario: priorización.*\
Dado* que quiero poder ordenarlas por prioridad, *cuando* cargo o edito
una, *entonces* tengo que poder registrar si se trata de una bloqueante,
una crítica, una mayor, una menor o una trivial.

### Gráfico 1

![](media/image3.png){width="5.99375in" height="3.877083333333333in"}

### Gráfico 2

![](media/image4.png){width="5.995833333333334in"
height="1.738888888888889in"}

## Anexo B: Sitio de Subastas

### Escenario

En estos sitios, una persona que se registra es denominada usuario y
tiene capacidad de publicar avisos, comprar o vender. Un usuario puede
publicar un aviso para dar a conocer sus productos o servicios con la
intención de venderlos. En este caso es denominado vendedor. También
puede elegir un aviso y realizar una oferta con la intención de comprar
el artículo promocionado por el mismo. En estos casos es denominado
comprador.

Existen modos de publicación. Cuando un vendedor publica un aviso
promocionando un producto o servicio que puede ser directamente comprado
por cualquier comprador hasta agotar el stock, se dice que el modo de
publicación es compra inmediata. También existe un modo especial de
publicación, denominado subasta, en el cual un vendedor indica que el
artículo promocionado por el aviso será vendido sólo al mejor postor. Se
fija un precio base y una duración para la subasta. Los compradores
realizan ofertas que deberán superar el precio base y todas las ofertas
anteriores. Finalizado el plazo de duración de la subasta, quién hubiere
realizado la mejor oferta, se transforma en el ganador de la subasta y
es quien efectivamente compró el artículo.

Para mantener bajo el nivel de complejidad y permitir la comprensión del
dominio en poco tiempo, teniendo en cuenta que aun así es posible
mostrar una variedad de patrones de diseño y técnicas de modelado de
interés, fue elegido como núcleo del trabajo la modalidad de publicación
denominada subasta. Esto significa que no se desarrollaron historias de
usuario relacionadas con el registro, modificación o baja de usuarios,
la publicación, modificación o cancelación de avisos o los listados en
general. Fundamentalmente, esas historias pueden ser consideradas
ejemplos de altas, bajas y modificaciones o listados y son ampliamente
tratados -quizás hasta el hartazgo- en la mayoría de los ejemplos de
aplicación empresarial propuestos, razón por la cual no fueron
consideradas oportunas.

### Historias de Usuario

1\. Crear subasta: como vendedor dueño de un aviso cuyo modo de
publicación es compra inmediata, quiero crear a partir del mismo una
subasta por el total del stock para llamar la atención de los
compradores y vender más rápidamente el remanente.

El precio base es el producto del precio unitario del artículo
promocionado por el aviso por la cantidad en stock. La fecha de inicio
es la fecha actual y la fecha de finalización es dada. El modo de
publicación del aviso pasa a subasta.

2\. Cancelar subasta: como vendedor dueño de una subasta en curso, quiero
cancelar la misma para evitar que el stock en venta sea adquirido de
esta forma.

Si la subasta no finalizó y si no tiene oferentes, se la finaliza. Esto
significa que ya no podrá aceptar ofertas u originar una compra. El modo
de publicación del aviso pasa a compra inmediata y puede ser comprado
normalmente.

3\. Realizar oferta: como comprador, quiero ofertar un monto en una
subasta para adquirir el producto en venta en caso de ganarla.

Esta oferta es aceptada solo en caso de que simultáneamente la subasta
no esté finalizada, el monto ofertado supere el precio base en caso de
que no hubiera otras ofertas y el monto ofertado sea mayor a la mejor
oferta en caso de que sí las hubiera. Se informa al comprador si su
oferta fue aceptada o no. Se registran todas las ofertas realizadas.

4\. Realizar oferta automática: como comprador, quiero realizar una
oferta automática en una subasta para adquirir el producto en venta en
caso de ganarla sin tener que realizar múltiples ofertas.

Una oferta automática es una oferta en la que el comprador no indica el
monto que oferta sino el monto máximo que está dispuesto a ofertar. La
oferta automática valdrá lo mínimo necesario para superar al resto de
las ofertas ya realizadas o por realizarse, hasta el máximo definido por
el comprador. Este valor mínimo con el cual superará a otras ofertas
puede ser un porcentaje del precio base, estar tabulado o ser un monto
fijo.

5\. Modificar precio base: como vendedor dueño de una subasta en curso,
quiero modificar el precio base de la misma para adecuarlo a mis
necesidades.

La subasta debe estar en curso y no haber recibido ofertas.


## Licencia

![Alt text](http://i.creativecommons.org/l/by-nc/3.0/88x31.png)

[Creative Commons Atribución-NoComercial 3.0 Unported](http://creativecommons.org/licenses/by-nc/3.0/)

