---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.FreeTextAnnotation. Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene un estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible.
type: docs
weight: 1810
url: /es/net/aspose.pdf.annotations/freetextannotation/
---
## Clase FreeTextAnnotation

Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene un estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Constructor para usar con Generator. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Crea una nueva anotación de texto libre en la página especificada. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtiene la lista de acciones de anotación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtiene o establece el estado de apariencia actual de la anotación. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtiene o establece las características del borde de la anotación. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Array de puntos que especifica la línea de llamada. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtiene o establece el color de la anotación. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtiene o establece el texto de la anotación. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtiene la fecha y hora en que se creó la anotación. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Obtiene o establece la cadena de apariencia predeterminada que se utilizará para formatear el texto. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Objeto que representa la apariencia predeterminada de la anotación de texto libre. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Obtiene o establece una cadena de estilo predeterminado. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Obtiene o establece el estilo de finalización de línea para el punto de finalización de línea. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtiene el nombre completamente calificado de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtiene o establece la altura de la anotación. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Una referencia a la anotación a la que esta anotación está "en respuesta". Ambas anotaciones deben estar en la misma página del documento. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Obtiene o establece la intención de la anotación de texto libre. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Obtiene o establece un código que especifica la forma de justificación que se utilizará para mostrar el texto de la anotación. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtiene o establece la fecha y hora en que se modificó recientemente la anotación. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtiene o establece el valor de opacidad constante que se utilizará al pintar la anotación. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtiene el índice de la página que contiene la anotación. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotación emergente para ingresar o editar el texto asociado con esta anotación. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtiene o establece el rectángulo de la anotación. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y una especificada por InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtiene o establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Ángulo de rotación de la anotación. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Obtiene o establece el estilo de inicio de línea para el punto de inicio de línea. Esta propiedad está obsoleta, por favor use EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtiene el texto que representa la descripción del objeto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Rectángulo que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Obtiene o establece el estilo del texto en la apariencia. Cuando se cambia el estilo del texto, se actualiza la apariencia del texto. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtiene o establece un texto que se mostrará en la barra de título de la anotación. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Acepta un objeto visitante para procesar la anotación. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Actualiza los parámetros y la apariencia, de acuerdo con la transformación de la matriz. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Limpia el estado y el modelo de estado de la anotación. Por ejemplo, limpia el estado de revisión de una anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instancia. Método virtual. Siempre devuelve null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Coloca el contenido de la anotación directamente en la página, el objeto de anotación será eliminado. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtiene el estado de la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtiene el modelo de estado de la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Establece el estado Marcado y No Marcado para la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Modelo de Estado de Revisión. El estado es establecido por el usuario que creó la anotación objetivo. El valor se toma de la propiedad Título de la anotación objetivo. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Modelo de Estado de Revisión. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |

### Ver También

* clase [MarkupAnnotation](../markupannotation/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblaje [Aspose.PDF](../../)