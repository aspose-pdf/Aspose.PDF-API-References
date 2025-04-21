---
title: Class ColorBarAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.ColorBarAnnotation. Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se utiliza el color ColorsOfCMYK. Al crearla, la relación de ancho y alto determina la orientación de la anotación horizontal o vertical. A continuación, se verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho para que la anotación se ajuste fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto se puede establecer en cero.
type: docs
weight: 1600
url: /es/net/aspose.pdf.annotations/colorbarannotation/
---
## Clase ColorBarAnnotation

Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se utiliza el color ColorsOfCMYK. Al crearla, la relación de ancho y alto determina la orientación de la anotación: horizontal o vertical. A continuación, se verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación se ajuste fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto se puede establecer en cero (en este caso, la anotación está presente en la página, pero no se muestra).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Página, Rectángulo, ColorsOfCMYK) | Crea una nueva anotación ColorBar en la página especificada. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtiene la lista de acciones de la anotación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtiene o establece el estado de apariencia actual de la anotación. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtiene o establece las características del borde de la anotación. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtiene o establece el color de la anotación. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | Obtiene o establece el color (uno de cian, magenta, amarillo, negro) para el cual se está dibujando la anotación. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtiene o establece el texto de la anotación. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtiene el nombre completo calificado de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtiene o establece la altura de la anotación. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para la generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para la generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para la generación de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtiene o establece la fecha y hora en que se modificó recientemente la anotación. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtiene el índice de la página que contiene la anotación. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtiene o establece el rectángulo de la anotación. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | Acepta un objeto visitante para procesar la anotación. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | Actualiza parámetros y apariencia, de acuerdo con la transformación de la matriz y moviéndose fuera del TrimBox si es necesario. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instancia. Método virtual. Siempre devuelve null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Coloca el contenido de la anotación directamente en la página, el objeto de anotación será eliminado. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |

### Véase también

* clase [PrinterMarkAnnotation](../printermarkannotation/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblado [Aspose.PDF](../../)