# Sketch

## Sketch

Sketch es la herramienta principal del estudio. Sketch forma parte del día a día del estudio, con la cual se diseña en la mayoría de los proyectos.

En este apartado se detalla cómo utilizamos Sketch, la organización que seguimos y los plugins que utilizamos.

## 1. Organización

La organización básica de nuestros archivos de Sketch se basa en páginas, _artboards_, símbolos y estilos compartidos.

### 1.1 Páginas

En nuestros archivos de Sketch se pueden encontrar tres tipos de páginas, en función de su contenido y del estado de este.

**Páginas en proceso 🔩**

Las páginas en proceso son sobre las que se está trabajando. En estas se itera sobre un mismo _artboard_ o elemento.

Consideramos importante diferenciar las páginas en las cuales no hay diseño acabado porque se está trabajando sobre ellas. Son páginas en las cuales el contenido no tiene que ser perfecto.

**Páginas** _**master**_ **✅**

Las páginas _master_ contienen el contenido acabado. El contenido de esta página debe estar perfecto, contar con estilos aplicados, estar formadas en base a componentes y respetar los espaciados definidos.

**Página de símbolos \(**_**Symbols**_**\)**

En la mayoría de nuestros proyectos, esta página **únicamente aparece cuando el archivo se trate de una librería,** la cual contiene sistema de diseño de nuestro producto.

![Nomenclatura que usamos en las p&#xE1;ginas de Sketch](../.gitbook/assets/sketch-pages-nomenclature.jpg)

{% hint style="info" %}
Esta es nuestra organización, no tiene porqué ser siempre así, pero esta es la que nos ayuda a nosotros a resolver conflictos sobre que páginas están listas y sobre cuales se está trabajando.
{% endhint %}

Para reflejar estos tres tipos de páginas y mantener los archivos de Sketch consistentes en todos los proyectos definimos que todas las páginas deben contar con un identificador visual, un identificador numerico y un nombre descriptivo de su contenido.

Siendo su nomenclatura:

```text
[Emoji] [nombre página]
```

* Emoji: utilizamos ✅ para páginas master y ⚙ para páginas en proceso.

Un ejemplo sería:

* ✅ Account
* ✅ Catalog
* ⚙️ Profile

### 1.2 Artboard

Nosotros agrupamos los _artboards_ en flujos o historias de usuario. Cada fila representa un posible flujo de la aplicación o de la web que se esté diseñando. Al principio de cada fila existe un _artboard_ que contiene el nombre y una descripción del flujo que representan los _artboards_ de dicha fila.

Para nombrar los artboards utilizamos un identificador, que se corresponde con el de la página, y un número que se compone con el número de fila y el número de vista.

```text
[id]_[numero fila][número vista]
```

* El id hace referencia al id de la página

  ✏️ Si la página es 01 Account → id página: 01

* El número de fila hace referencia al número de flujo en el que estemos situados

Un ejemplo sería:

Primer flujo → número fila: 1

Segundo flujo → número fila: 2

Tercer flujo → número fila: 3

* El número de vista será incremental de izquierda a derecha.

  ✏️ Si 01 02 03 04 05 06 07 08 09 10 11 12

Un ejemplo sería:

Para los flujos en la página en 01 Account:

* 01\_100 01\_101 01\_102 01\_103
* 01\_200 01\_201 01\_202 01\_203 01\_204
* 01\_300 01\_301 01\_302 01\_303

### 1.3 Símbolos

Utilizamos símbolos para optimizar y automatizar trabajo, los símbolos nos facilita el cambio en múltiples componentes simultáneamente.

La raíz de los símbolos en Sketch está situada en una Librería de Sketch, vinculada archivo de Sketch en el que estamos trabajando. El uso de librerías nos permite que todos los archivos de Sketch de un mismo proyecto compartan componentes y evitar duplicidades que nos lleven al error.

{% hint style="info" %}
✏️ Para conocer más sobre como trabajamos con símbolos y componentes puedes leer **4. Sistemas de diseño**.
{% endhint %}

### 1.4 Estilos compartidos

Trabajamos con dos tipos de estilos compartidos, estilos de texto y estilos de capa.

Normalmente estos van a residir en la librería en la cual se encuentra el sistema de diseño de nuestro proyecto, y se aplicarán en el archivo en el que estemos trabajando.

Los estilos, como nos símbolos y componentes, nos ayudan a evitar inconsistencias y duplicidades.

**Estilos de capa**

Entre los estilos de capa podemos diferenciamos entre color, opacidad y sombras.

* Color

  Los estilos de texto deben coincidir con la paleta de colores del producto. Estos los creamos tanto en color fill como en outline.

* Opacidad \(_Opacity_\)

  Nosotros aplicamos las opacidades al grupo contenedor del elemento o elementos que se quiere que tengan una opacidad determinada. Así, controlamos que opacidades se utilizan en el proyecto. Eso nos permite actualizar estilos de capa y texto sin perder las diferentes opacidades que tengan las instancias de dicho estilo.

* Sombras \(_Shadows_\)

**Estilos de texto**

En todos nuestr archivos, los textos tienen que tener un estilo de texto asignado. Esto nos ayuda a mantener la consistencia en el archivo y en el producto.

## 2. Sketch plugins

A continuación se detallan 5 plugins de Sketch que nos facilitan el día a día en trabajando con la herramienta 🚀.

### 2.1 [**Sketch Runner**](https://sketchrunner.com/)

_Sketch Runner_ nos ayuda a buscar _todoloqueimagines_ dentro de Sketch, aplicar estilos e insertar símbolos.

![Captura de pantalla del modal de Sketch Runner](../.gitbook/assets/screenshot-sketch-runner.png)

Sketch Runner permite:

* Ejecutar plugins
* Instalar plugins
* Ir a cualquier página, artboard, grupo o _layer_ en el documento de Sketch que nos encontramos
* Insertar símbolos
* Crear símbolos
* Crear estilos de texto y estilos de capa
* Aplicar estilos de texto y estilos de capa
* Actualizar plugins obsoletos

### 2.2 [**Automate Sketch**](https://github.com/Ashung/Automate-Sketch/)

Algunas de las cosas que puedes hacer con este plugin y que nos hacen el día más fácil son:

* Remplazar fuentes \(_Replace Fonts_\)
* Importar estilos de una librería  \(_Import Styles from Library_\)
* Reemplazar símbolos con símbolos de una librería  \(_Replace Symbol with Library Symbol_\)
* Renombrar instancias de símbolos  \(_Rename Instances_\)
* Seleccionar capas por estilo de capa o por estilo de texto  \(_Select Layer by Layer / Text Style_\)
* Redimensionar artboards para que se ajusten a la altura de las capas y grupos que contiene \(_Resize to Fix Height_\)

### 2.3 [**Rename It**](https://rodi01.github.io/RenameIt/)

_Rename It_ permite:

* Renombrar capas \(_Rename Selected Layers_\)
* Renombrar _artboards_ \(_Rename Artboards_\)
* Remplazar palabras por otras  \(_Find and Replace_\)

Para nosotros es muy útil porque nos permite añadir secuencias de números de forma ascendiente o descendiente de forma automática, lo que nos permite nombrar los _artboards_ fácilmente.

![Captura de pantalla de la ventana de Rename It](../.gitbook/assets/screenshot-rename-it.png)

### 2.4 [**Sketch Style Master**](https://github.com/aparajita/sketch-style-master)

Es igual que _Rename It_, pero para estilos de texto. Es realmente útil ya que te deja cambiar el nombre de los estilos de texto y remplazar palabras de estos.

![Captura de pantalla de la ventana de Sketch Style Master](../.gitbook/assets/screenshot-text-style-master.png)

### 2.5 [**Sketch Style Inventory**](https://github.com/getflourish/Sketch-Style-Inventory)

Una de las grandes ventajas de este plugin es poder sacar todos los estilos de texto que existen en el archivo. Al ejecutar el plugin, _Sketch Style Inventory_ crea una página con todos los estilos de texto que haya.

![Captura de pantalla del modal de Sketch Style Inventory](../.gitbook/assets/screenshot-style-inventory.png)

Es realmente útil cuando se necesita cambiar alguna característica de los estilos, ya que de esta forma podemos asegurar que el cambio se ha aplicado a todos los estilos de texto.

_Sketch Syle Inventory_ también puede generar todos los colores y símbolos presentes en el archivo de Sketch, incluso exportarlos.

### 2.6 [**Sketch Page Numbers**](https://github.com/getflourish/Sketch-Style-Inventory)

Este plugin permite añadir numeración a los artboards en Sketch de tal forma que estos se numeran según el orden en el que aparecen en el listado de capas \(también pueden numerarse en orden inverso\).

![Captura de pantalla de la ventana de Sketch Page Numbers](../.gitbook/assets/screenshot-sketch-page-number.png)

Es de gran ayuda sobre todo a la hora de diseñar documentos en Sketch como brandbooks o presentaciones de conceptos.

