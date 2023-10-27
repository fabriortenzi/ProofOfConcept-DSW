# SVELTE


## ¿Qué es Svelte?
Svelte proporciona una metodología diferente para construir aplicaciones web. Mientras otros frameworks como React y Vue hacen la mayor parte del trabajo en el navegador del usuario mientras se ejecuta la aplicación, Svelte convierte esa carga de trabajo en un proceso de compilación que se ejecuta a la hora de construir (build) la aplicación, produciendo así código Javascript puro (vanilla) altamente optimizado.
Tras usar esta metodología, como resultado no solo tenemos aplicaciones menos pesadas y rápidas, sino que también mejora la experiencia de creación de aplicaciones para las personas que tienen poca experiencia con el ecosistema moderno de herramientas de desarrollo.
Svelte adopta en gran medida el modelo clásico de desarrollo web dado por HTML, JS y CSS, pues solamente añade unas cuantas extensiones sobre HTML y JavaScript. A diferencia del resto de frameworks, Svelte probablemente introduce menos conceptos y herramientas por aprender.

#### *Historia*
Svelte se originó a partir de Ractive.js, que fue desarrollado por el propio creador de Svelte Rich Harris. Svelte fue diseñado para suceder a Ractive. La primera versión de Svelte lanzada en 2016 era básicamente Ractive, pero con un compilador.
El nombre Svelte fue elegido por Rich Harris y sus compañeros de trabajo en The Guardian. Con el paso del tiempo, cada vez más desarrolladores conocieron Svelte y se interesaron por él. En 2019, Svelte se había convertido en una herramienta de pleno derecho para crear aplicaciones web compatibles con TypeScript.
El framework web SvelteKit se anunció en 2020 y entró en fase beta en 2021.

#### *¿Cómo funciona Svelte?*
Al tratarse de un compilador, Svelte puede extender HTML, CSS, y JavaScript, generando código Javascript optimizado sin agregar sobrecarga en tiempo de ejecución. Para lograr esto, Svelte añade características sobre tecnologías web nativas de la siguiente forma:
- Extiende a HTML al permitir expresiones de JavaScript dentro del marcado HTML, proporcionando directivas para utilizar condiciones y ciclos.
- Extiende a CSS al agregar mecanismos de contención, permitiendo a cada componente definir sus propios estilos sin el riesgo de que colisionen con estilos de otros componentes.
- Extiende a JavaScript al reinterpretar directivas específicas del lenguaje para lograr verdadera reactividad y facilitar el manejo del estado de los componentes.
<br></br>

## Svelte vs React
#### *Análisis Técnico*
Cuando se ejecuta la compilación de producción de una aplicación Svelte, Svelte compila
su código en JavaScript vanilla altamente optimizado. Esto significa que no se agrega el codigo del framework en tiempo de ejecución, lo que mejora la calidad de la aplicación y
rendimiento general porque el navegador tiene menos trabajo que hacer.

Svelte actualiza el DOM sin depender de intermediarios o cualquier técnica compleja de reconciliación. El compilador de Svelte rastrea los cambios en sus variables y actualiza el HTML en consecuencia. Mira a través de su código y busca componentes que dependen de sus variables, luego actualiza esos componentes a medida que cambian las variables. De esta manera, Svelte es reactivo sin tener que depender de una API de terceros.

Tanto Svelte como React siguen una arquitectura de desarrollo basada en componentes, pero la diferencia radica en que React utiliza JSX, mientras que Svelte es un lenguaje en sí mismo compuesto por los tres lenguajes estándar: HTML, CSS y JavaScript.
###
#### *Tiempo de desarrollo*

Una de las características más distintivas de Svelte es su enfoque en la eficiencia en tiempo de compilación. A diferencia de otros frameworks, Svelte realiza la mayor parte del trabajo pesado en el momento de la compilación. Esto significa que la generación de código y la optimización se producen antes de que la aplicación se ejecute. Como resultado, se reduce significativamente el tiempo necesario para renderizar la interfaz de usuario. Por otro lado, El tamaño del paquete generado por Svelte tiende a ser más pequeño en comparación con otros marcos. Esto es beneficioso para la carga rápida de la aplicación y una experiencia de usuario más ágil. La eficiencia en tiempo de ejecución de Svelte, junto con un tamaño de paquete reducido, contribuye a un rendimiento óptimo de la aplicación.

Además, Svelte se esfuerza por una mejor legibilidad, y reducción de la cantidad de código necesario para construir una aplicación. Esto se logra a través de una sintaxis concisa y la eliminación de la necesidad de código de "boilerplate". En comparación con otros marcos, como React, donde la cantidad de código puede ser considerablemente mayor, Svelte ofrece un enfoque más directo y legible para la creación de aplicaciones. Esto no solo acelera el tiempo de desarrollo, sino que también facilita el mantenimiento a largo plazo.

En términos de dificultad del lenguaje, Svelte se destaca por su simplicidad y facilidad de aprendizaje. La mayor parte de Svelte se compone de JavaScript, HTML y CSS estándar. No es necesario aprender nuevos conceptos o sintaxis especiales, como JSX, lo que acelera la curva de aprendizaje para los desarrolladores. Además, la documentación de Svelte es conocida por ser muy accesible y cuenta con un tutorial detallado incorporado, lo que facilita aún más la adopción de esta tecnología.

Sin embargo, es importante recordar que el tiempo de desarrollo puede variar según las necesidades del proyecto y la experiencia del desarrollador. La elección de Svelte como marco de desarrollo puede influir significativamente en la rapidez y eficiencia del proceso de desarrollo.
###
#### *Comunidad*
La comunidad de usuarios de un framework de desarrollo desempeña un papel esencial en su crecimiento y éxito. Svelte es conocido como el «framework JavaScript más querido» con los «desarrolladores más satisfechos», presumiendo de más de 60.000 estrellas en el repositorio de GitHub. Evaluaremos la comunidad que rodea a Svelte, un framework de desarrollo frontend, y la compararemos con la comunidad de React, uno de los marcos más populares. Analizaremos métricas clave y recursos disponibles para comprender la salud y vitalidad de ambas comunidades.
##### Comunidad de Usuarios de Svelte
Svelte cuenta con una comunidad activa y comprometida, con varios indicadores notables:
- **GitHub y Repositorio de Svelte**:
    + *Estrellas (Stars)*: el repositorio de Svelte en GitHub (https://github.com/sveltejs/svelte) tiene un gran número de estrellas, lo que indica un alto nivel de interés y adopción por parte de la comunidad
    + *Contribuciones (Contributors)*: el repositorio cuenta con una comunidad sólida de contribuyentes activos que trabajan en mejoras, correcciones de errores y nuevas características.
    + *Issues y Pull Requests*: la comunidad de Svelte mantiene un flujo constante de issues y pull requests, lo que demuestra una alta actividad y compromiso en la mejora del framework.
- **Recursos de la Comunidad**:
    + El sitio web oficial de Svelte (https://svelte.dev) ofrece una documentación detallada y recursos de aprendizaje, lo que facilita su adopción.
    + La comunidad se reúne en foros y grupos de discusión en línea, como el subreddit de Svelte (r/sveltejs en Reddit) y el foro oficial de Svelte.
    + Se han desarrollado numerosas bibliotecas y complementos relacionados con Svelte, lo que muestra una colaboración activa y la extensión de sus capacidades.
    + Svelte ha estado presente en conferencias y eventos relacionados con JavaScript y desarrollo web, lo que refleja el interés y la difusión del conocimiento en la comunidad.
###
##### Comparativa con la Comunidad de React
React es uno de los marcos más populares y ampliamente adoptados en el desarrollo frontend. Al comparar las comunidades de Svelte y React, observamos las siguientes diferencias:
- **GitHub y Repositorio de React**:
    - React tiene un repositorio oficial en GitHub (https://github.com/facebook/react) con un número significativamente mayor de estrellas en comparación con Svelte. Esto refleja la gran adopción y popularidad de React.
######
- **Recursos de la Comunidad**:
    - React ofrece una gran cantidad de recursos de la comunidad, como la documentación oficial (https://reactjs.org), foros, grupos de discusión y una amplia variedad de bibliotecas y complementos desarrollados por la comunidad.
    - React también cuenta con una amplia comunidad de contribuyentes activos, pero debido a su longevidad y popularidad, la comunidad es considerablemente más grande que la de Svelte.
    - React ha sido el foco de numerosas conferencias y eventos en todo el mundo, lo que demuestra su presencia a nivel global en el desarrollo web.


Ambas comunidades, tanto la de Svelte como la de React, son activas y comprometidas. Svelte ha ganado rápidamente popularidad y se ha convertido en una opción atractiva para el desarrollo frontend, con una comunidad en crecimiento y una sólida presencia en GitHub. Sin embargo, React sigue siendo un gigante en términos de adopción y comunidad, con una gran base de usuarios y un amplio ecosistema de recursos.
React gana en apoyo de la comunidad. Los desarrolladores de React también están muy solicitados en comparación con Svelte.
<br></br>
## Popularidad
State of Javascript es una página web que desde 2016 recolecta datos de más de veinte mil desarrolladores cada año, con el objetivo de identificar tendencias actuales y futuras en el mundo del lenguaje Javascript. 
Para evaluar una tecnología, este sitio divide el total de sus encuestados en 3 categorías: Los que la han usado (dividido en quiénes lo usarían de nuevo y quienes no lo usarían de nuevo), los que no la han usado (dividido en quiénes desean aprenderlo y quienes no desean aprenderlo) y quienes no han escuchado de ella. La tecnología a evaluar se mide en los siguientes aspectos:
- **Uso**: porcentaje respecto del total de los encuestados, que han usado el producto.
- **Interés**: porcentaje, respecto del total de personas que no han usado el producto pero lo conocen, que está interesada en aprenderlo.
- **Conciencia**: porcentaje, respecto del total de los encuestados, que ha oído hablar del producto.
- **Retención**: porcentaje, respecto del total de encuestados que han usado el producto, que volverían a utilizarlo.


Según los resultados arrojados en las investigaciones del año 2022, Svelte es conocido por el 93,5% de los desarrolladores de la comunidad, solo por detrás de Angular, Vue.js y React (el 99,9% lo conoce) en ese aspecto.
Svelte tiene fama de ser el framework con desarrolladores más satisfechos, y esto se ve en su porcentaje de retención que es del 89,7% lo que denota que la gran mayoría de usuarios que utilizan esta tecnología, desean volver a utilizarla en otro momento. Este alto porcentaje es el segundo mayor, tan solo superado por Solid y 6,7% arriba de React. 
Svelte es además el que mayor nivel de interés muestra por parte de los programadores. De aquellos que no lo han utilizado, el 70% está interesado en darle un vistazo a la tecnología.
Sin embargo, únicamente el 21% de los encuestados dijeron haber usado Svelte, sustancialmente menos que los frameworks de front-end populares mencionados anteriormente. En cambio, cuatro de cada cinco desarrolladores, ha utilizado React.
<br></br>
##Documentación oficial
Svelte provee una documentación completa dividida en diferentes secciones para usuarios ya adentrados en el framework, o sea, se requiere un mínimo de conocimientos para comenzar a leer la misma. La experiencia necesaria, puede ser obtenida mediante el tutorial oficial de la página de Svelte. Allí uno puede aprender, con código en tiempo real, los conceptos de la tecnología, desde los más básicos a niveles de mayor complejidad: Svelte básico y Svelte avanzado, además de una complementación con un tutorial de Sveltekit. Existen, además, proyectos de ejemplo para tener como referencia.
Los conceptos de sintaxis de templates componen la primera sección. La misma está destinada a los Svelte Components, los bloques de lógica, tags especiales, directivas de elementos (tales como los modificadores de eventos), directivas de componentes y elementos especiales. Las explicaciones son concisas y contienen código que las respaldan. 
Luego, se incluyen detalles acerca de los packages de Svelte, bajo una sección llamada Runtime. Nuevamente nos encontramos con porciones de lógica escrita en el lenguaje de programación y su respectiva descripción en lenguaje inglés. En este caso, cada sección contiene información completa y detallada sobre las funciones y tipos a los que se puede acceder al importar el paquete en cuestión.
Finalmente, aparecen dos secciones más: Compilador y API, y por último una sección de misceláneas. La primera informa sobre el funcionamiento del Svelte Compiler y sobre las API de componentes Server-Side y Client-Side. La segunda, incluye respuestas a preguntas frecuentes, métodos que utiliza Svelte para lograr una correcta.
<br></br>
## Ventajas y desventajas del uso de Svelte
###
### *Ventajas*
#### No utiliza virtual DOM
El DOM se actualiza y manipula el HTML de forma directa. Si hay una actualización, se crea un nuevo DOM y se vuelven a pintar todos los elementos que formen parte del documento.  El virtual es una representación del DOM real en la memoria del navegador, una copia del DOM actual. Siempre que haya un cambio en algún elemento de la UI, un nuevo Virtual DOM es creado. Entonces, el nuevo y el anterior se comparan uno a uno y se comprueban qué diferencias existen entre ambos. Como resultado, se accede al DOM real pintando únicamente aquello que se ha actualizado, sin la necesidad de refrescar todos los componentes del documento.
En lugar de replicar el DOM de manera virtual en memoria -con el coste que puede tener en aplicaciones grandes- y compararlos en busca de cambios para actualizar el DOM donde haya cambiado, directamente se ejecutan las operaciones necesarias en el DOM cuando el estado de la aplicación cambia. Y este enfoque funciona porque al ser un compilador, sabe en tiempo de construcción cómo las cosas podrían cambiar en la aplicación en lugar de esperar a hacer el trabajo en tiempo de ejecución, dando como resultado aplicaciones más ligeras y más rápidas.

#### Excelente manejo de estados y reactividad
Svelte es un framework que se destaca por su facilidad y versatilidad a la hora de manejar estados (state management). Cuando se habla de estados, se hace referencia al valor o situación actual en la que se encuentra un elemento uilizado para el desarrollo, como puede ser un objeto, una variable o un componente, entre otros. Un ejemplo simple de esto podría ser el de una variable de nombre var (definida como "let var = 1"), la cual puede pasar de contener un 1 a un 0 (luego, "var = 0"), produciéndose entonces un cambio de estado en este elemento, debiéndose actualizar el DOM para poder reflejarlo.
Svelte brinda diferentes herramientas, muy útiles, para poder hacer frente a estos cambios de estado, de una forma simple y más eficiente que la mayoría del resto de los frameworks de front-end. Las más destacadas son:
##### *Context API de Svelte*
La Context API de Svelte es perfecta para la comunicación entre componentes sin tener que complicar el código pasando props de un lado a otro. Esta herramientaa se habilita mediante dos funciones incorporadas en Svelte, getContext y setContext. Es posible hacer que un objeto o valor esté disponible en cualquier parte de la aplicación al establecerlo en el Context y asociarlo con una clave, como se muestra en el ejemplo de código a continuación:

`<script>`

`import { setContext } from 'svelte'`

`const thisObject = {}`

`setContext('thisKey', thisObject)`

`</script>`

Para hacer que thisKey esté disponible en un componente diferente dentro de la aplicación, simplemente de lo debe importar utilizando la función getContext:

`<script>`

`import { getContext } from 'svelte'`

`const thisObject = getContext('thisKey')`

`</script>`

Es importante tener en cuenta que solo se puede utilizar getContext para recuperar una clave en el componente que utilizó setContext, o en un componente dentro del mismo árbol de componentes. Para comunicar propiedades y valores entre dos componentes en árboles diferentes, Svelte utiliza stores.


##### *Svelte Stores*

A medida que una aplicación crece en tamaño, tiende a aumentar en complejidad. En este punto, no es una gran idea anidar ciertas partes del estado de la aplicación en la jerarquía de componentes de la misma, pues habrá algunas propiedades que necesitarán ser accedidas por diferentes componentes.

Svelte maneja este tipo de propiedad a través de "stores" o almacenes, que son objetos que contienen un valor y pueden notificar cuando ese valor cambia. Svelte tiene dos tipos de stores para manejar el estado en las aplicaciones: "writable" y "readable".

Los **writable stores** son objetos que contienen valores o propiedades a los que pueden acceder diferentes componentes dentro de una aplicación. Como ejemplo, se puede usar un writable store para mantener un valor que luego se podrá modificar o pasar por toda la aplicación. Para acceder a este valor, se lo debe exportarlo desde el store y guardarlo en un archivo JavaScript, de la siguiente manera:

` (ubicándonos dentro de un archivo 'location.js')`

`<script>`

`import writable from 'svelte/store'`

`export const city = writable('New York')`

`</script>`

Luego se lo puede importar en cualquier otro componente donde sea necesario de la siguiente manera:

`<script>`

`import { city } from './location.js'`

`</script>`

El valor en un writable store puede ser modificado. Si se necesita cambiar el valor de city en cualquier componente donde se importa, se puede utilizar el método set():

`<script>`

`import { city } from './location.js'`

`city.set('Washington')`

`</script>`

O bien, se puede utilizar el método update() para ejecutar una devolución de llamada que recibe el valor actual como argumento:

`<script>`

`import { city } from './location.js'`

`const newCity = 'Washington'`

`function changeCity() {city.update(existing => newCity)}`

`</script>`

Como alternativa, es posible hacer que los componentes estén atentos a los cambios en el valor que se establece en la store, utilizando el método subscribe() de Svelte:

`<script>`

`import { city } from './location.js'`

`const watch = city.subscribe(value => {console.log(value)});`

`</script>`

Al igual que los writable stores, los **readable stores** contienen objetos, pero no pueden ser actualizados desde componentes externos. Cuando se usa un readable store, se debe establecer su valor cuando al ser creado. Los readable stores se utilizan principalmente para manejar datos que deben ser inmutables.

Un ejemplo completo de un store se podrá ver con autos, en https://github.com/fabriortenzi/ProofOfConcept-DSW/blob/main/src/store/cars_example.js .


##### *Equal sign / assing operator*
Es importante recordar que Svelte es un lenguaje en sí mismo, lo cual hace que este conjunto de syntactic sugar al que uno se expone a usarlo pueda ser algo confunso al principio. En este caso, para el manejo del estado de una variable, se pueden hacer uso de eventos que son disparados luego de que ocurra algo (on:click={someFunction}, por ejemplo), como en prácticamente todos los frameworks de front-end. Lo que distingue a Svelte en este caso, es el cómo se consigue que la variable (u objeto) cambie su estado, a partir de que el evento, luego de ser disparado, llame a una función definida en el script del componente correspondiente. Esto se consigue únicamente si se hace uso del **assing operator ("=")**. Svelte advierte el cambio de estado de una variable/objeto **únicamente si su valor está siendo reasignado**. De cualquier otra forma, la acción reactiva que está intentando ser ejecutada tendrá un resultado nulo.
Entonces, Svelte solo se preocupa por las variables que están siendo reasignadas, no por los valores a los que esas variables hacen referencia. Si la variable que se reasigna no está definida en el nivel superior (script), Svelte no desencadena una actualización, incluso si el valor que se está actualizando, actualiza también el valor original de la variable.


##### *Reactive declarations*
Además del sistema de reactividad basado en asignaciones, Svelte también tiene una sintaxis especial para definir código que debe ejecutarse de nuevo cuando cambian sus dependencias, utilizando declaraciones etiquetadas con "$:", llamadas **reactive declarations**. Estas se definen en el nivel superior (script).
Cuando Svelte encuentra una reactive declaration, se asegura de ejecutar cualquier otra reactive declaration que dependa entre sí, en el orden correcto, y solo cuando sus dependencias directas hayan cambiado. Una "dependencia directa" es una variable que se referencia dentro de la propia declaración reactiva. Las referencias a variables dentro de funciones que llaman una declaración reactiva no se consideran dependencias.
De esta forma, Svelte brinda una forma muy sencilla de comprender y utilizar (consta, como se aclaró, simplemente de un $:, seguido de cualquier expresión de asignación JavaScript), para poder manejar el estado de variables/objetos dentro de un componente, en forma reactiva.


#### Fácil aprendizaje
Como se habrá notado durante este informe, para poder hacer uso de Svelte, vastaría con tener conocimientos sobre HTML, CSS y JavaScript (o, en su defecto, TypeScript). Está claro que Svelte, como lenguaje, ha añadido algo de syntactic sugar a JavaScript para facilitar la usabilidad del framework tal como de ha descrito antes, pero se trata de conceptos mínimos (aunque útiles), cuya inversión de tiempo vale totalmente la pena.
Es muy probable que la mayoría de las personas que estén leyendo este informe prefieran aprender la mínima sintaxis que ofrece Svelte en, por ejemplo, las reactive declarations ($:), antes que lidiar con el problema de los hooks de React (como useState).


#### Scoped styling
Svelte proporciona, en lugar de CSS tradicional, un scoped styling (estilo acotado) con JavaScript. Este le brinda a los desarrolladores la posibilidad de incluir estilos en la mitad del archivo .svelte, los cuales se encuentran acotados a un componente específico, y a sus hijos. 


#### Aplicaciones más rápidas y menos pesadas

Este punto ya se ha desarrollado antes en mayor profundidad (durante la sección de Tiempo de desarrollo), pero vale la pena mencionar esta ventaja nuevamente, pues es una de las características del framework front-end que probablemente lo posicionen entre los más usados dentro de unos años.
Svelte genera el código y lo optimiza de forma previa a que la aplicación se comience a utilizar. Esto disminuye el tiempo de carga de las pantallas, aportando una mejor experiencia de usuario (UX).
Además, el tamaño del paquete generado por Svelte es bastante pequeño, lo cual también aporta a la disminución de tiempo de carga de la aplicación. Mejora entonces, también, la UX.


##
### *Desventajas*

#### Ecosistema, soporte y comunidad relativamente pequeños.
Svelte comenzó a hacerse más popular durante el año 2019, por lo que puede considerarse como uno de los frameworks front-end más exitosos si se considera que ha estado en el mercado masivo por tan poco tiempo. Sin embargo, esta tecnología todavía se encuentra "verde" con respecto a otros frameworks, como React. Esto hace que la comunidad de Svelte sea bastante reducida, con un ecosistema y soporte pequeños que hacen que los desarrolladores no cuenten con demasiadas alternativas de personalización y modificación actualmente.
De todas formas, como se ha mencionado anteriormente en este informe, la comunidad de Svelte es, aunque pequeña, bastante fiel y activa, por lo que se puede preveer un buen futuro en este aspecto para esta herramienta.



#### Menor popularidad que otros JS frameworks.
Svelte, al ser uno de los frameworks de front-end más novedosos de la industria, se encuentra en la posición de tener que competir contra otros gigantes que forman parte de la columna vertebral del desarrollo de software moderno, como lo son React, Angular o Vue. Por esta razón, Svelte no es tan popular actualmente, encontrándose bastante menos establecido en el mercado.
De todas formas, las tendencias dan a entender que esto se podría revertir más temprano que tarde debido a sus numerosas ventajas, siempre y cuando se continúe con las buenas decisiones que se han tomado durante su existencia.
<br></br>
## Conclusión general
El objetivo principal de una prueba de concepto (Proof of Concept, POC) es obtener la suficiente información sobre alguna tecnología, de cualquier índole, para poder comprenderla a fondo y, en base a esto, poder tomar una decisión con respecto a si es conveniente o no hacer inclusión de la misma en cierto proyecto (ya sea actual o futuro).
Con respecto a Svelte, ha sido posible conocer que se trata de un framework front-end relativamente moderno, con amplias ventajas en términos de manejo de estados y reactividad, en conjunto con velocidad a la hora de crear y actualizar a la aplicación gracias a su método de compilación y su carencia de Virtual DOM. Si bien son claros los beneficios de esta tecnología, personalmente, como estudiantes y personas con poca experiencia en el desarrollo de software, pensamos que elegir a Svelte no sería la mejor alternativa, principalmente por dos puntos fundamentales:
- **Falta de énfasis en las buenas prácticas del desarrollo y escalabilidad**
A comparación de, por ejemplo, Angular (que es el que hemos estado usando), el framework Svelte cuenta con todo el código de un componente en un mismo archivo .svelte. Esto, si bien acelera el proceso de desarrollo, hace que personas que están aprendiendo (como nosotros) sean más propensas a ignorar la reutilización de código, manteniendo al componente como una entidad simple en cuanto a cantidad de archivos, pero sumamente compleja internamente (pues cuenta con el HTML, CSS y funcionalidad JavaScript a la vez). Todo esto dificulta enormemente la escalabilidad.
#####
- **Pequeña comunidad y bajo mercado**
Como ya se ha mencionado, Svelte es un framework relativamente nuevo y, al tener que competir con otros ya más establecidos en el mercado como React, Vue o Angular, este sale perdiendo en cuanto a popularidad. Especializarse en Svelte sin saber otro framework (es decir, elegir como primera opción a Svelte), sería probablemente un gran error pues actualmente es una tecnología bastante de nicho, dificultándose conseguir un trabajo que no sea únicamente para un proyecto temporal o meramente personal. Para estudiantes como nosotros, es más conveniente comenzar por herramientas más establecidas en el mercado y, luego, analizar otras tecnologías más novedosas.

En resumen, si se trata de un proyecto no muy grande, y la persona que lo elige ya cuenta con experiencia previa, Svelte es una maravillosa herramienta que facilita bastante el desarrollo, mejorando la developer experience (experiencia del desarrollador). Luego, en contraste, si se trata de alguien que todavía está aprendiendo, y se encuentra intentando crear una aplicación de tamaño mediano/grande, lo más recomendable sería optar por otra opción, como Angular, React o Vue.