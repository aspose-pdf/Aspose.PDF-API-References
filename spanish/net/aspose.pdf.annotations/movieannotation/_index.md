---
title: MovieAnnotation
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una anotación de película que contiene gráficos animados y sonido para ser presentado en la pantalla de la computadora ya través de los parlantes. Cuando se activa la anotación se reproduce la película.
type: docs
weight: 730
url: /es/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Representa una anotación de película que contiene gráficos animados y sonido para ser presentado en la pantalla de la computadora ya través de los parlantes. Cuando se activa la anotación, se reproduce la película.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MovieAnnotation](movieannotation#constructor)(Document, string) | Constructor para usar con Generator. |
| [MovieAnnotation](movieannotation#constructor_1)(Page, Rectangle, string) | Crea una nueva anotación de sonido en la página especificada. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtiene la lista de acciones de anotación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtiene o establece el estado actual de apariencia de la anotación. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect) { get; set; } | Obtiene o establece el ancho y el alto del cuadro delimitador de la película, en píxeles. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtiene o establece las características del borde de la anotación.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtiene o establece el color de la anotación. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtiene o establece el texto de la anotación. |
| [File](../../aspose.pdf.annotations/movieannotation/file) { get; set; } | Obtiene o establece una especificación de archivo que identifica un archivo de película autodescriptivo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtiene el nombre calificado completo de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtiene o establece la altura de la anotación. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtiene o establece que un párrafo está en línea. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtiene o establece un valor booleano que obliga a generar este párrafo en una nueva página. El valor predeterminado es falso. (para la generación de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el párrafo siguiente. El valor predeterminado es falso. (para la generación de PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtiene o establece la fecha y la hora en que se modificó recientemente la anotación. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtiene el índice de la página que contiene la anotación. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster) { get; set; } | Obtiene o establece un indicador o secuencia que especifica si se mostrará una imagen de póster que represente la película y cómo. Si es verdadero, la imagen del póster se recuperará del archivo de la película; si es falsa, no se exhibirá ningún cartel. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Obtiene o establece el rectángulo de anotación. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate) { get; set; } | Obtiene o establece el número de grados por los que se girará la película en el sentido de las agujas del reloj en relación con la página. El valor será un múltiplo de 90. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| [Title](../../aspose.pdf.annotations/movieannotation/title) { get; set; } | Obtiene o establece el título de la anotación de la película. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept)(AnnotationSelector) | Acepta objeto visitante para procesar la anotación. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Actualizar parámetros y apariencia, según la transformada de matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona esta instancia. Método virtual. Devuelve siempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Coloca el contenido de la anotación directamente en la página, se eliminará el objeto de anotación. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Devuelve el rectángulo de anotación teniendo en cuenta la rotación de página. |

### Ver también

* class [Annotation](../annotation)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
