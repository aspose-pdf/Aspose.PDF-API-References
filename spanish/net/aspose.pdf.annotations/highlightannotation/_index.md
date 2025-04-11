---
title: Class HighlightAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.HighlightAnnotation. Representa una anotación de resaltado que resalta un rango de texto en el documento
type: docs
weight: 1870
url: /es/net/aspose.pdf.annotations/highlightannotation/
---
## Clase HighlightAnnotation

Representa una anotación de resaltado que resalta un rango de texto en el documento.

```csharp
public sealed class HighlightAnnotation : TextMarkupAnnotation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HighlightAnnotation](highlightannotation/)(Página, Rectángulo) | Crea una nueva anotación de resaltado en la página especificada. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtiene la lista de acciones de anotación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtiene o establece el estado de apariencia actual de la anotación. |
| override [AnnotationType](../../aspose.pdf.annotations/highlightannotation/annotationtype/) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtiene o establece las características del borde de la anotación. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtiene o establece el color de la anotación. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtiene o establece el texto de la anotación. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtiene la fecha y hora en que se creó la anotación. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtiene el nombre completamente calificado de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtiene o establece la altura de la anotación. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Una referencia a la anotación a la que esta anotación está "en respuesta". Ambas anotaciones deben estar en la misma página del documento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtiene o establece la fecha y hora en que se modificó recientemente la anotación. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtiene o establece el valor constante de opacidad que se utilizará al pintar la anotación. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtiene el índice de la página que contiene la anotación. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotación emergente para ingresar o editar el texto asociado con esta anotación. |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints/) { get; set; } | Obtiene o establece un array de puntos que especifican las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o grupo de palabras contiguas en el texto subyacente a la anotación. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtiene o establece el rectángulo de la anotación. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y una especificada por InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtiene o establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtiene el texto que representa la descripción del objeto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtiene o establece un texto que se mostrará en la barra de título de la anotación. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/highlightannotation/accept/)(AnnotationSelector) | Acepta un objeto visitante para procesar la anotación. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize/)(Matrix) | Actualiza los QuadPoints, de acuerdo con la transformación de la matriz. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Limpia el estado y el modelo de estado de la anotación. Por ejemplo, limpia el estado de revisión de una anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instancia. Método virtual. Siempre devuelve null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Coloca el contenido de la anotación directamente en la página, el objeto de anotación será eliminado. |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext/)() | Obtiene el texto bajo la anotación de marcado como cadena. |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments/)() | Obtiene el texto bajo la anotación de marcado como [`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection/). |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtiene el estado de la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtiene el modelo de estado de la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Establece el estado Marcado y No Marcado para la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Modelo de Estado de Revisión. El estado es establecido por el usuario que creó la anotación objetivo. El valor se toma de la propiedad Título de la anotación objetivo. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Modelo de Estado de Revisión. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |

### Ver También

* clase [TextMarkupAnnotation](../textmarkupannotation/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblaje [Aspose.PDF](../../)