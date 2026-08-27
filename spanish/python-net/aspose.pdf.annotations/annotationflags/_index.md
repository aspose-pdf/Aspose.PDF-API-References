---
title: "AnnotationFlags"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Un conjunto de indicadores que especifican varias características de la anotación."
type: docs
weight: 930
url: /es/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Un conjunto de indicadores que especifican varias características de la anotación.

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| DEFAULT | Valor predeterminado. |
| INVISIBLE | Si está activado, no muestre la anotación si no pertenece a uno de los tipos de anotación estándar<br/>            y no hay un controlador de anotaciones disponible. Si está desactivado, muestre esa anotación desconocida<br/>            usando un flujo de apariencia especificado por su diccionario de apariencia, si lo hay. |
| HIDDEN | Si está activado, no muestre ni imprima la anotación ni permita que interactúe con el usuario,<br/>            sin importar su tipo de anotación o si hay un controlador de anotaciones disponible.<br/>            En casos donde el espacio en pantalla es limitado, la capacidad de ocultar y mostrar anotaciones selectivamente<br/>            puede usarse en combinación con flujos de apariencia para mostrar información auxiliar emergente<br/>            similar en función a los sistemas de ayuda en línea. |
| IMPRIMIR | Si está activado, imprima la anotación cuando se imprima la página. Si está desactivado, nunca imprima la anotación,<br/>            sin importar si se muestra en pantalla. Esto puede ser útil, por ejemplo, para anotaciones<br/>            que representan botones pulsables interactivos, los cuales no tendrían un propósito significativo en la página impresa. |
| NO_ZOOM | Si está activado, no escale la apariencia de la anotación para que coincida con la ampliación de la página.<br/>            La ubicación de la anotación en la página (definida por la esquina superior izquierda de su rectángulo de anotación)<br/>            permanece fija, sin importar la ampliación de la página. |
| NO_ROTATE | Si está activado, no rote la apariencia de la anotación para que coincida con la rotación de la página.<br/>            La esquina superior izquierda del rectángulo de anotación permanece en una ubicación fija en la página,<br/>            sin importar la rotación de la página. |
| NO_VIEW | Si está activado, no muestre la anotación en la pantalla ni permita que interactúe con el usuario.<br/>            La anotación puede imprimirse (según la configuración de la bandera Print)<br/>            pero debe considerarse oculta a efectos de la visualización en pantalla y la interacción del usuario. |
| READ_ONLY | Si está activado, no permita que la anotación interactúe con el usuario. La anotación puede mostrarse<br/>            o imprimirse (según la configuración de las banderas NoView y Print) pero no debe responder a clics<br/>            del ratón ni cambiar su apariencia en respuesta a movimientos del ratón. Esta bandera se ignora para anotaciones de widget;<br/>            su función está subsumida por la bandera ReadOnly del campo de formulario asociado. |
| LOCKED | Si está activado, no permita que la anotación sea eliminada ni que sus propiedades (incluyendo posición y tamaño)<br/>            sean modificadas por el usuario. Sin embargo, esta bandera no restringe los cambios en el contenido de la anotación,<br/>            como el valor de un campo de formulario. |
| TOGGLE_NO_VIEW | Si está establecido, invierte la interpretación de la bandera NoView para ciertos eventos.<br/>            Un uso típico es tener una anotación que aparece solo cuando se mantiene el cursor del ratón sobre ella. |
| LOCKED_CONTENTS | Si está establecido, no permite que el usuario modifique el contenido de la anotación.<br/>            Esta bandera no restringe la eliminación de la anotación ni los cambios a otras propiedades de la anotación,<br/>            como la posición y el tamaño. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

