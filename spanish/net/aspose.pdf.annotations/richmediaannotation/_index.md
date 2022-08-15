---
title: RichMediaAnnotation
second_title: Referencia de API de Aspose.PDF para .NET
description: La clase describe RichMediaAnnotation que permite incrustar datos de video/audio en un documento PDF.
type: docs
weight: 1030
url: /es/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

La clase describe RichMediaAnnotation que permite incrustar datos de video/audio en un documento PDF.

```csharp
public class RichMediaAnnotation : Annotation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation)(Page, Rectangle) | Inicializa RichMediaAnnotation. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtiene la lista de acciones de anotación. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon) { get; set; } | Evento que activa la aplicación. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtiene o establece el estado actual de apariencia de la anotación. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtiene o establece las características del borde de la anotación.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtiene o establece el color de la anotación. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content) { get; } | Datos del contenido de Rich Media. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtiene o establece el texto de la anotación. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables) { get; set; } | Establece u obtiene variables flash que pasan al jugador. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer) { get; set; } | Establece u obtiene un reproductor flash personalizado para reproducir datos de video/audio. |
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
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Obtiene o establece el rectángulo de anotación. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type) { get; set; } | Obtiene o establece el tipo de contenido. Valores posibles: Audio, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept)(AnnotationSelector) | Acepta visitante para esta anotación. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata)(string, Stream) | Agregar datos con nombre personalizados (por ejemplo, requeridos para flash script). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Actualizar parámetros y apariencia, según la transformada de matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona esta instancia. Método virtual. Devuelve siempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Coloca el contenido de la anotación directamente en la página, se eliminará el objeto de anotación. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Devuelve el rectángulo de anotación teniendo en cuenta la rotación de página. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent)(string, Stream) | Establecer flujo de contenido. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter)(Stream) | Establecer cartel de la anotación. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update)() | Actualiza datos con parámetros especificados. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [ActivationEvent](richmediaannotation.activationevent) | Evento que activa la anotación. |
| enum [ContentType](richmediaannotation.contenttype) | Tipo de multimedia. |

### Ver también

* class [Annotation](../annotation)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
