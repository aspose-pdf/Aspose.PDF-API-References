---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Enum AnnotationFlags de Aspose.Pdf.Annotations. Un conjunto de flags que especifican varias características de la anotación
type: docs
weight: 1440
url: /es/net/aspose.pdf.annotations/annotationflags/
---
## Enumeración AnnotationFlags

Un conjunto de flags que especifican varias características de la anotación.

```csharp
[Flags]
public enum AnnotationFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | `0` | Valor predeterminado. |
| Invisible | `1` | Si está establecido, no mostrar la anotación si no pertenece a uno de los tipos de anotación estándar y no hay un controlador de anotaciones disponible. Si se borra, mostrar tal anotación desconocida utilizando un flujo de apariencia especificado por su diccionario de apariencia, si lo hay. |
| Hidden | `2` | Si está establecido, no mostrar ni imprimir la anotación ni permitir que interactúe con el usuario, independientemente de su tipo de anotación o de si hay un controlador de anotaciones disponible. En casos donde el espacio en pantalla es limitado, la capacidad de ocultar y mostrar anotaciones selectivamente puede usarse en combinación con flujos de apariencia para mostrar información auxiliar emergente similar en función a los sistemas de ayuda en línea. |
| Print | `4` | Si está establecido, imprimir la anotación cuando se imprima la página. Si se borra, nunca imprimir la anotación, independientemente de si se muestra en la pantalla. Esto puede ser útil, por ejemplo, para anotaciones que representan botones interactivos, que no tendrían un propósito significativo en la página impresa. |
| NoZoom | `8` | Si está establecido, no escalar la apariencia de la anotación para que coincida con la magnificación de la página. La ubicación de la anotación en la página (definida por la esquina superior izquierda de su rectángulo de anotación) permanece fija, independientemente de la magnificación de la página. |
| NoRotate | `10` | Si está establecido, no rotar la apariencia de la anotación para que coincida con la rotación de la página. La esquina superior izquierda del rectángulo de anotación permanece en una ubicación fija en la página, independientemente de la rotación de la página. |
| NoView | `20` | Si está establecido, no mostrar la anotación en la pantalla ni permitir que interactúe con el usuario. La anotación puede ser impresa (dependiendo de la configuración del flag Print) pero debe considerarse oculta para fines de visualización en pantalla e interacción del usuario. |
| ReadOnly | `40` | Si está establecido, no permitir que la anotación interactúe con el usuario. La anotación puede ser mostrada o impresa (dependiendo de las configuraciones de los flags NoView y Print) pero no debe responder a clics del mouse ni cambiar su apariencia en respuesta a movimientos del mouse. Este flag es ignorado para anotaciones de widget; su función es subsumida por el flag ReadOnly del campo de formulario asociado. |
| Locked | `80` | Si está establecido, no permitir que la anotación sea eliminada o que sus propiedades (incluyendo posición y tamaño) sean modificadas por el usuario. Sin embargo, este flag no restringe cambios en el contenido de la anotación, como el valor de un campo de formulario. |
| ToggleNoView | `100` | Si está establecido, invertir la interpretación del flag NoView para ciertos eventos. Un uso típico es tener una anotación que aparece solo cuando un cursor de mouse se mantiene sobre ella. |
| LockedContents | `200` | Si está establecido, no permitir que el contenido de la anotación sea modificado por el usuario. Este flag no restringe la eliminación de la anotación o cambios en otras propiedades de la anotación, como posición y tamaño. |

### Ver También

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)