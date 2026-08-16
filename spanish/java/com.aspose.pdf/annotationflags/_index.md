---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Flags Conjunto de banderas binarias que especifican diversas características de la anotación."
type: docs
weight: 90
url: /es/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Flags Conjunto de banderas binarias que especifican diversas características de la anotación.

## Campos

| Campo | Descripción |
| --- | --- |
| [Default](#Default) | Valor predeterminado. |
| [Hidden](#Hidden) | Si está activado, no se muestra ni imprime la anotación ni se permite que interactúe con el usuario, independientemente de su tipo de anotación o de si hay un controlador de anotaciones disponible. En casos donde el espacio en pantalla es limitado, la capacidad de ocultar y mostrar anotaciones de forma selectiva puede usarse en combinación con flujos de apariencia para mostrar información auxiliar emergente similar en función a los sistemas de ayuda en línea. |
| [Invisible](#Invisible) | Si está activado, no se muestra la anotación si no pertenece a uno de los tipos de anotación estándar y no hay un controlador de anotaciones disponible. Si está desactivado, se muestra dicha anotación desconocida utilizando un flujo de apariencia especificado por su diccionario de apariencia, si lo hay. |
| [Locked](#Locked) | Si está activado, no permita que la anotación sea eliminada ni que sus propiedades (incluyendo posición y tamaño) sean modificadas por el usuario. Sin embargo, esta bandera no restringe los cambios en el contenido de la anotación, como el valor de un campo de formulario. |
| [LockedContents](#LockedContents) | Si está activado, no permita que el contenido de la anotación sea modificado por el usuario. Esta bandera no restringe la eliminación de la anotación ni los cambios en otras propiedades de la anotación, como posición y tamaño. |
| [NoRotate](#NoRotate) | Si está activado, no rote la apariencia de la anotación para que coincida con la rotación de la página. La esquina superior izquierda del rectángulo de la anotación permanece en una ubicación fija en la página, sin importar la rotación de la página. |
| [NoView](#NoView) | Si está activado, no muestre la anotación en la pantalla ni permita que interactúe con el usuario. La anotación puede imprimirse (según la configuración de la bandera Print) pero debe considerarse oculta a efectos de la visualización en pantalla y la interacción del usuario. |
| [NoZoom](#NoZoom) | Si está activado, no escale la apariencia de la anotación para que coincida con la ampliación de la página. La ubicación de la anotación en la página (definida por la esquina superior izquierda de su rectángulo de anotación) permanece fija, sin importar la ampliación de la página. |
| [Print](#Print) | Si está activado, imprima la anotación cuando la página se imprima. Si está desactivado, nunca imprima la anotación, sin importar si se muestra en la pantalla. Esto puede ser útil, por ejemplo, para anotaciones que representan botones interactivos, los cuales no tendrían un propósito significativo en la página impresa. |
| [ReadOnly](#ReadOnly) | Si está activado, no permita que la anotación interactúe con el usuario. La anotación puede mostrarse o imprimirse (según la configuración de las banderas NoView y Print) pero no debe responder a clics del ratón ni cambiar su apariencia en respuesta a movimientos del ratón. Esta bandera se ignora para anotaciones de widget; su función está subsumida por la bandera ReadOnly del campo de formulario asociado. |
| [ToggleNoView](#ToggleNoView) | Si está activado, invierta la interpretación de la bandera NoView para ciertos eventos. Un uso típico es tener una anotación que aparezca solo cuando el cursor del ratón se mantiene sobre ella. |

### Default {#Default}
```
public static final int Default
```

Valor predeterminado.

### Hidden {#Hidden}
```
public static final int Hidden
```

Si está activado, no se muestra ni imprime la anotación ni se permite que interactúe con el usuario, independientemente de su tipo de anotación o de si hay un controlador de anotaciones disponible. En casos donde el espacio en pantalla es limitado, la capacidad de ocultar y mostrar anotaciones de forma selectiva puede usarse en combinación con flujos de apariencia para mostrar información auxiliar emergente similar en función a los sistemas de ayuda en línea.

### Invisible {#Invisible}
```
public static final int Invisible
```

Si está activado, no se muestra la anotación si no pertenece a uno de los tipos de anotación estándar y no hay un controlador de anotaciones disponible. Si está desactivado, se muestra dicha anotación desconocida utilizando un flujo de apariencia especificado por su diccionario de apariencia, si lo hay.

### Locked {#Locked}
```
public static final int Locked
```

Si está activado, no permita que la anotación sea eliminada ni que sus propiedades (incluyendo posición y tamaño) sean modificadas por el usuario. Sin embargo, esta bandera no restringe los cambios en el contenido de la anotación, como el valor de un campo de formulario.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Si está activado, no permita que el contenido de la anotación sea modificado por el usuario. Esta bandera no restringe la eliminación de la anotación ni los cambios en otras propiedades de la anotación, como posición y tamaño.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Si está activado, no rote la apariencia de la anotación para que coincida con la rotación de la página. La esquina superior izquierda del rectángulo de la anotación permanece en una ubicación fija en la página, sin importar la rotación de la página.

### NoView {#NoView}
```
public static final int NoView
```

Si está activado, no muestre la anotación en la pantalla ni permita que interactúe con el usuario. La anotación puede imprimirse (según la configuración de la bandera Print) pero debe considerarse oculta a efectos de la visualización en pantalla y la interacción del usuario.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Si está activado, no escale la apariencia de la anotación para que coincida con la ampliación de la página. La ubicación de la anotación en la página (definida por la esquina superior izquierda de su rectángulo de anotación) permanece fija, sin importar la ampliación de la página.

### Print {#Print}
```
public static final int Print
```

Si está activado, imprima la anotación cuando la página se imprima. Si está desactivado, nunca imprima la anotación, sin importar si se muestra en la pantalla. Esto puede ser útil, por ejemplo, para anotaciones que representan botones interactivos, los cuales no tendrían un propósito significativo en la página impresa.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Si está activado, no permita que la anotación interactúe con el usuario. La anotación puede mostrarse o imprimirse (según la configuración de las banderas NoView y Print) pero no debe responder a clics del ratón ni cambiar su apariencia en respuesta a movimientos del ratón. Esta bandera se ignora para anotaciones de widget; su función está subsumida por la bandera ReadOnly del campo de formulario asociado.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Si está activado, invierta la interpretación de la bandera NoView para ciertos eventos. Un uso típico es tener una anotación que aparezca solo cuando el cursor del ratón se mantiene sobre ella.
