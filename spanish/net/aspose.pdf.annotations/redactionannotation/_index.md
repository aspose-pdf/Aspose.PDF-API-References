---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.RedactionAnnotation. Representa la anotación de redacción
type: docs
weight: 2400
url: /es/net/aspose.pdf.annotations/redactionannotation/
---
## Clase RedactionAnnotation

Representa la anotación de redacción.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | Constructor para RedactionAnnotation. Para usar en Generator. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | Constructor para RedactAnnotation. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtiene la lista de acciones de anotación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtiene o establece el estado de apariencia actual de la anotación. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtiene o establece las características del borde de la anotación. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Obtiene o establece el color del borde que se dibuja cuando la redacción no está activa. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtiene o establece el color de la anotación. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtiene o establece el texto de la anotación. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtiene la fecha y hora en que se creó la anotación. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Obtiene o establece la cadena de apariencia predeterminada que se utilizará para formatear el texto. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Obtiene o establece el color para llenar la anotación. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Banderas de la anotación. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Obtiene o establece el tamaño de fuente para OverlayText. |
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
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtiene o establece el valor de opacidad constante que se utilizará al pintar la anotación. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Obtiene o establece el texto para imprimir en la anotación de redacción. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtiene el índice de la página que contiene la anotación. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotación emergente para ingresar o editar el texto asociado con esta anotación. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Un arreglo de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtiene o establece el rectángulo de la anotación. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Si es verdadero, el texto superpuesto se repetirá en la anotación. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y una especificada por InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtiene o establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtiene el texto que representa la descripción del objeto. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Obtiene o establece la alineación del texto superpuesto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtiene o establece un texto que se mostrará en la barra de título de la anotación. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Acepta un objeto visitante para procesar la anotación. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Actualiza parámetros y apariencia, de acuerdo con la transformación de la matriz. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Limpia el estado y el modelo de estado de la anotación. Por ejemplo, limpia el estado de revisión de una anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instancia. Método virtual. Siempre devuelve null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Aplana la anotación, es decir, elimina la anotación y agrega su |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtiene el estado de la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtiene el modelo de estado de la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Aplana la anotación y redacta el contenido de la página (es decir, elimina texto e imagen bajo la anotación redactada) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Establece el estado Marcado y No Marcado para la anotación. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Modelo de Estado de Revisión. El estado es establecido por el usuario que creó la anotación objetivo. El valor se toma de la propiedad Título de la anotación objetivo. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Modelo de Estado de Revisión. Nota: el estado se almacena en otra anotación de texto que tiene claves de estado y modelo de estado. |

### Ver También

* clase [MarkupAnnotation](../markupannotation/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblaje [Aspose.PDF](../../)