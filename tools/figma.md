# Figma

Figma nos permite trabajar de forma colaborativa, online y en tiempo real. Además, Figma nos permite realizar todo el proceso que realizamos en Sketch. Figma es una gran alternativa para realizar ejercicios de ideación y definición cuando el equipo no puede estar de forma presencial. 

El porqué utilizamos más Sketch que Figma es porque con Sketch nuestro proceso está mucho más automatizado gracias a los plugins y más controlado gracias a Abstract.

Figma es una gran alternativa para realizar ejercicios de ideación y definición cuando el equipo no puede estar de forma presencial. 

En cuanto a cómo trabajamos con Figma el proceso se mantiene igual que el que realizamos en Sketch. 

## Páginas

En nuestros archivos de Sketch se pueden encontrar tres tipos de páginas, en función de su contenido y del estado de este.

**Páginas en proceso 🔩** 

Las páginas en proceso son sobre las que se está trabajando. En estas se itera sobre un mismo *artboard* o elemento.

Consideramos importante diferenciar las páginas en las cuales no hay diseño acabado porque se está trabajando sobre ellas. Son páginas en las cuales el contenido no tiene que ser perfecto. 

**Páginas *master* ✅** 

Las páginas *master* contienen el contenido acabado. El contenido de esta página debe estar perfecto, contar con estilos aplicados, estar formadas en base a componentes y respetar los espaciados definidos.

**Página de componentes (*Components*)** 

Donde residen los componentes que componen el  sistema de diseño.

Esta es nuestra organización, no tiene porqué ser siempre así, pero esta es la que nos ayuda a nosotros a resolver conflictos sobre que páginas están listas y sobre cuales se está trabajando.

Para reflejar estos tres tipos de páginas y mantener los archivos de Sketch consistentes en todos los proyectos definimos que todas las páginas deben contar con un identificador visual, un identificador numerico y un nombre descriptivo de su contenido. 

Siendo su nomenclatura:

[Emoji] [id] [nombre página]

- Emoji: utilizamos ✅ para páginas master y 🔩 para páginas en proceso.
- Los identificadores numéricos serán números incrementales precedidos por un 0.

 

Un ejemplo sería: 

- ✅ 01 Account
- ✅ 02 Catalog
- ✅ 03 Profile
- 🔩 03 Profile

## *Frames*

Nosotros agrupamos los *frames* en flujos o historias de usuario. Cada fila representa un posible flujo de la aplicación o de la web que se esté diseñando. Al principio de cada fila existe un *artboard* que contiene el nombre y una descripción del flujo que representan los *artboards* de dicha fila. 

Para nombrar los artboards utilizamos un identificador, que se corresponde con el de la página, y un número que se compone con el número de fila y el número de vista.  

[id]_[numero fila][número vista]

- El id hace referencia al id de la página

 ✏️ Si la página es 01 Account → id página: 01

- El número de fila hace referencia al número de flujo en el que estemos situados

 

Un ejemplo sería: 

Primer flujo → número fila: 1

Segundo flujo → número fila: 2

Tercer flujo → número fila: 3

- El número de vista será incremental de izquierda a derecha.

     ✏️ Si 01 02 03 04 05 06 07 08 09 10 11 12 

     

 

Un ejemplo sería: 

Para los flujos  en la página en 01 Account:

- 01_100 01_101 01_102 01_103
- 01_200 01_201 01_202 01_203 01_204
- 01_300 01_301 01_302 01_303

## Components

Utilizamos componentes para optimizar y automatizar trabajo, ya que nos facilita el cambio en múltiples componentes simultáneamente.

En Figma, los componentes pueden pertenecer al archivo o pertenecer al *Team Library.* El *Team Library* es el repositorio de componentes compartidos por todas las personas que pertecezcan al equipo. En nuestro caso, la *Team Library* es compartida por todos los archivos de mendesaltaren. 

Los componentes en Figma no son lo mismo que los símbolos en Sketch. Al utilizar un componente se crea una instancia y no una copia de este. Esto permite que las propiedades de color y texto de los elementos que componen una instancia se pueden cambiar, lo único que no se puede modificar es la posición. 

## Estilos compartidos

**Estilos de color**

Una peculiaridad de Figma con respecto a Sketch es que no tiene estilos de capa como tal, sino que son estilos de color únicamente. Los estilos de color se pueden aplicar tanto en bordes y los rellenos de una capa como en los estilos de texto. Esto, para nosotros tiene dos ventajas claves:

- No tenemos que crear tantos estilos de capa, diferenciando entre cuando es un borde (*outline*) y cuando se trata de un relleno (*fill*).
- No tenemos que crear un estilo de texto por cada color que se vaya a utilizar. Creamos unos estilos de texto base y sobre estos aplicamos estilos de color definidos.

**Estilos de texto**

Los estilos de texto también difieren en cuanto a cómo son los estilos de textos en Sketch. En Figma para cada estilo de texto únicamente queda reflejado el tamaño, la altura de caja y el peso. La alineación puede ser modificada. 

Esto nos permite que cada vez que creamos un estilo de texto, no haya que crear uno distinto para cada alineación (izquierda, centro y derecha). Únicamente creamos uno y al utilizarlo lo modificamos. 

---