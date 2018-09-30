# Zeplin

Con Zeplin conseguimos estrechar el gap entre diseño y desarrollo.

Para garantizar que lo que está en Zeplin es el diseño final, únicamente subimos los archivos que están en la rama _Master_ del proyecto en Abstract.

## 1. Crear un proyecto nuevo en Zeplin

Los proyectos en Zeplin se crean de acuerdo a la siguiente nomenclatura para mantener la consistencia entre los nombres de los proyectos en las distintas herramientas.

```text
[id proyecto][Nombre del proyecto][Plataforma]
```

* El campo de plataforma es opcional. Nos sirve para concretar si los artboards que contiene dicho proyecto son de web o de app iOS o Android .

Por ejemplo, si crearamos un nuevo proyecto en Zeplin para exportar el diseño de Playtomic Web:

* id proyecto → 19
* Nombre del proyecto → Playtomic
* Plataforma → Web

```text
19_Playtomic_Web
```

{% hint style="info" %}
✏️ Para conocer más sobre como nos organizamos y cual nomenclatura de archivos que seguimos puedes encontrarlo en [**1. Cómo nos organizamos**](../organization.md).
{% endhint %}

## 2. Preparar Sketch para subir a Zeplin

Marcar elementos necesarios como exportables para desarrollo. Estamos hablando de los assets del proyecto como los iconos o las imágenes.

## 3. Exportar los _Artboards_ o _Frames_

La forma de exportar las vistas dependerá de si trabajamos con Sketch o con Figma.

**Sketch**

Si estamos trabajando con Sketch, al descargarnos Zeplin se nos ha descargado un plugin de Sketch, el cual utilizaremos para realizar la exportación.

**Figma**

Para exportar los _Frames_ desde Figma debemos activar Zeplin dentro de Figma y posteriormente utilizar el comando Option+E con los _frames_ que queramos exportar seleccionados. Este comando activará la activación a Zeplin de forma automática.

