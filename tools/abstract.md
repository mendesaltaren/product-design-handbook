# Abstract

## Abstract

En el equipo trabajamos con Abstract porque nos permite tener un control de versiones del producto y trabajar varias personas simultaneamente sobre un mismo archivo de Sketch, nuestra principal herramienta de trabajo.

Con Abstract hemos conseguido eliminar copias en conflicto, duplicados y confusiones sobre cuales son los archivos finales. Y además, nos ha permitido incluir a nuestros clientes en el flujo de trabajo, pudiendo estos visualizar el trabajo realizado y el estado en el que está proyecto.

{% hint style="info" %}
✏️ Para que los clientes puedan ver el proyecto deben estar invitados al proyecto y formar parte de los miembros de este.
{% endhint %}

En este apartado veremos cómo funciona Abstract y cómo lo utilizamos en el estudio en nuestro día a día.

## 1. Introducción

La estructura básica de abstract se compone de _Master_ y _Branches._ Su funcionamiento se basa en realizar _commits_ y _mergear_ ramas, o _branches_.

Los _commits_ representan los cambios que se han realizando. Un _commit_ puede entenderse como una foto a un archivo de Sketch en un momento determinado, permitiéndonos volver siempre que queramos a ese instante. El conjunto de _commits_ forman un histórico, donde están reflejados todos los cambios que se han realizado sobre los distintos archivos de Sketch que formen un proyecto. Esto nos permite tener conocimiento del trabajo realizado, y que ante cualquier ausencia no prevista, se pueda continuar con el trabajo sin ningún problema. Cualquier miembro del equipo podría seguir sin que se produzcan pérdidas de información, conocimiento y trabajo.

### 1.1 _Master_

El _Master_ es la _**Source of truth**_ de nuestros proyectos. Todo lo que contenga el _Master_ debe estar listo para poder validar el trabajo con el cliente o subir los diseños a Zeplin para producción.

### 1.2 Rama \(_branch_\)

Cada persona que trabaja en el proyecto, trabaja en una rama distinta. Cada rama pertenece a una persona distinta. Todas las ramas principales sobre las que se trabaje una nueva funcionalidad o un concepto deben partir del _Master_, ya que es allí donde están reflejados los últimos cambios _buenos_ realizados. Y una rama puede sostener otras, de forma que varias personas puedan trabajar sobre lo mismo y posteriormente se pueda unificar sin problemas el trabajo realizado.

Al realizar una rama se realiza una copia exacta de los archivos de su rama padre, bien sea el Master o la rama de otro compañero. Esto nos permite evitar pérdidas de información.


Para nosotros, ejemplos de ramas podrían ser:

* Branding
* Exploración visual
* Módulo de búsqueda
* Flujo del checkout
* Alineación navbar

Las ramas tienen un nombre y una descripción.

* El nombre debe ser descriptivo sobre lo que se va a trabajar en esta.
* La descripción debe complementar al nombre. Para nosotros, una buena descripción es aquella que contiene cuales son los requisitos para que la funcionalidad se complete o cual es el objetivo de ella. Así, cuando se haya cumplido se podrá _mergear_ con su _rama padre_.

## 2. ¿Cómo trabajamos en Abstract?

En este apartado compartiremos como utilizamos Abstract en el equipo, cual es nuestra metodología, nuestras pautas y procedimientos ante los distintos proyectos. A este proceso hemos llegado tras trabajar meses con la herramienta, pero para cada equipo y proyecto pueden funcionar de forma distinta.

### 2.1 Commit

{% hint style="info" %}
✏️ Un commit puede entenderse como una actualización de los archivos de Sketch en un momento de tiempo determinado, de forma que recoge todos los cambios que se han realizado hasta ese momento.
{% endhint %}

**¿Cuándo realizamos un commit?**

En el estudio, distinguimos entre tres tipos de _commits_, que representan tres momentos en los que se debe realizar un commit.

* Cada vez que se complete una tarea. Esto nos permite llevar un control sobre cuándo se llevó a cabo y cuales fueron los cambios realizados para completarla.
* En las ramas de concepto, a lo largo de la fase de exploración, realizamos un _commit_ cada vez que se cambia de dirección.
* Al finalizar el día. Siempre, cada uno de las personas del equipo debe hacer commit antes de cerrar el ordenador e irse a casa. Esto nos ayuda a que cualquiera pueda continuar el día siguiente con el trabajo, en el mismo punto que se dejó el día anterior.

{% hint style="info" %}
✏️ Las tareas coinciden con las tareas marcadas en [Asana](https://github.com/mendesaltaren/product-design-handbook/tree/e6917bdfb723014dd2c5e3ef24be95efb32f5370/tools/tools/asana.md), que es donde reflejamos el roadmap y las tareas a realizar en un proyecto.
{% endhint %}

**¿Cómo se realiza un commit?**

{% hint style="info" %}
✏️ Para hacer un commit habrá que clicar sobre _Preview and Commit_ en la bar que sale la parte inferior en Sketch. Al seleccionar esta opción, se cargan todas las pantallas añadidas o modificadas en Abstract para poder visualizar los cambios que se han realizado.
{% endhint %}

Para completar el commit, hay que incluir un nombre y una descripción de este. El nombre y la descripción nos dan contexto para cuando queramos visualizar _commits_ anteriores, y que sean los suficientemente claras es especialmente útil cuando queremos retroceder a un punto concreto.

El nombre debe ser descriptivo y la descripción contener los cambios realizados. Una buena práctica para dar nombre al _commit_ realizado es:

* Si el _commit_ se realiza tras haber completado una tarea, el nombre debe coincidir con el \[**nombre de la tarea\]**.
* Si el _commit_ se hace por haber finalizado el día, el nombre debe seguir la siguiente estructura:

  **Avanzar con \[nombre de la tarea\]**.

* Si el commit es en una rama de exploración, el nombre debe describir los cambios realizados

Para nosotros, la descripción es una lista de cambios que se han realizado entre un _commit_ y otro. Para que esta sea clara y fácil de entender por todos los miembros que formamos el equipo utilizamos la siguiente nomenclatura:

```text
✅ [Acción] [Donde se producido la acción]
```

**Un ejemplo sería:**

```text
✅ Añadir [artboard]
✅ Añadir [symbol]
✅ Añadir [página]
✅ Cambiar [módulo]
✅ Cambiar [symbol]
✅ Eliminar [módulo]
✅ Eliminar [página]
✅ Cambiar [página]
```

### 2.2 Merge

Cuando _mergeamos_ estamos unificando el archivo de Sketch. Al _mergear_ volvamos todos los artboards y páginas en los que hemos estado trabajando y hemos realizado cambios al archivo que se encuentra en la _rama padre_ desde la que hicimos la rama. Nosotros hacemos _merge_ cuando se completa el objetivo para el cual fue creada la rama en la que estábamos trabajando. Como por ejemplo, tras completar una funcionalidad.

Cuando _mergeamos_ una rama, Abstract nos da la opción de incluir detalles. Esto es importante cuando hay comunicar información al equipo sobre los cambios realizados en la rama, y queremos que esta quede reflejada.

Puede ocurrir que se modifique un mismo _artboard_ o un mismo símbolo en distintas ramas. Cuando esto ocurre, Abstract nos obliga a seleccionar con que opción nos quedamos. Es importante que esta decisión se tome junto con el equipo que esté participando en el proyecto, y comunicar finalmente cual es la decisión.

### 2.3 Añadir comentarios

Abstract nos permite añadir comentarios sobre los distintos elementos de un archivo de Sketch. Esto nos ayuda tanto a la comunicación interna como a la colaboración con el cliente y su equipo.

### 2.4 Crear nuevo proyecto en Abstract

Cada proyecto en el que trabajamos en el estudio, forma parte de un proyecto distinto en Abstract.

Los proyectos en Abstract tienen un nombre, una descripción y un color asignado.

* Para el nombre, mantenemos el nombre del proyecto tenemos en Dropbox. De esta forma, conseguimos mantener consistencia en las distintas herramientas con las que trabajamos.
* La descripción es interesante y recomendable que refleje la descripción del proyecto y sus objetivos a alcanzar.
* El color sirve como identificador visual del proyecto, por lo que es bueno que este sea el color principal de este.

### 2.5 Crear un nuevo archivo en Abstract

Para mantener los procesos, creamos los de Sketch direcamente en Abstract. Abstract, nos permite crear archivos de Sketch o bien librerías de Sketch. Las librerías que creamos en un proyecto quedan automáticamente vinculadas con todos los archivos que contenga este.

La **nomenclatura** de nuestros archivos de Sketch siguen el siguiente formato:

```text
[id archivo][tipo de archivo][Plataforma]
```

**Un ejemplo sería:**

```text
01_Research
02_UX_Web
02_UI_Web
02_UI
02_UI_App_Android
02_Design-System
```

{% hint style="info" %}
✏️ Para conocer más sobre como nos organizamos y cual nomenclatura de archivos que seguimos puedes encontrarlo en **1. Cómo nos organizamos**.
{% endhint %}

