---
title: TextMarkupAnnotation
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase base abstracta para anotaciones de marcado de texto.
type: docs
weight: 1220
url: /es/net/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation class

Clase base abstracta para anotaciones de marcado de texto.

```csharp
public abstract class TextMarkupAnnotation : MarkupAnnotation
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtiene la lista de acciones de anotación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtiene o establece el estado actual de apariencia de la anotación. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtiene o establece las características del borde de la anotación.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtiene o establece el color de la anotación. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtiene o establece el texto de la anotación. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Obtiene la fecha y la hora en que se creó la anotación. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtiene el nombre calificado completo de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtiene o establece la altura de la anotación. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Una referencia a la anotación a la que esta anotación es "en respuesta". Ambas anotaciones deben estar en la misma página del documento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtiene o establece que un párrafo está en línea. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtiene o establece un valor booleano que obliga a generar este párrafo en una nueva página. El valor predeterminado es falso. (para la generación de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el párrafo siguiente. El valor predeterminado es falso. (para la generación de PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtiene o establece la fecha y la hora en que se modificó recientemente la anotación. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Obtiene o establece el valor de opacidad constante que se utilizará para pintar la anotación. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtiene el índice de la página que contiene la anotación. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Anotación emergente para ingresar o editar el texto asociado con esta anotación. |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints) { get; set; } | Obtiene o establece una matriz de puntos que especifican las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Obtiene o establece el rectángulo de anotación. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y una especificada por InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Obtiene o establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Obtiene texto que representa la descripción del objeto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Obtiene o establece un texto que se mostrará en la barra de título de la anotación. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept)(AnnotationSelector) | Acepta visitante para procesamiento de anotaciones. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize)(Matrix) | Actualiza los QuadPoints, según la transformación de la matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona esta instancia. Método virtual. Devuelve siempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Coloca el contenido de la anotación directamente en la página, se eliminará el objeto de anotación. |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext)() | Obtiene el texto debajo de la anotación de marcado como una cadena. |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments)() | Obtiene el texto debajo de la anotación de marcado como[`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection) . |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Devuelve el rectángulo de anotación teniendo en cuenta la rotación de página. |

### Ver también

* class [MarkupAnnotation](../markupannotation)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
