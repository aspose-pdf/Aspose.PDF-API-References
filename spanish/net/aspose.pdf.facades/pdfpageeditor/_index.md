---
title: PdfPageEditor
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una clase para editar la página del archivo PDF incluida la rotación de página el zoom de página el movimiento de posición y el cambio de tamaño de página.
type: docs
weight: 2600
url: /es/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Representa una clase para editar la página del archivo PDF, incluida la rotación de página, el zoom de página, el movimiento de posición y el cambio de tamaño de página.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | Constructor para la clase PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | Constructor para la clase PdfPageEditor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | Obtiene o establece la duración de visualización de las páginas. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | Obtiene o establece la alineación horizontal del contenido del PDF original en la página de resultados; el valor predeterminado es AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | Una tabla hash contiene el número de página y el grado de rotación, la clave representa el número de página, el valor de la clave representa la rotación en grados. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | Obtiene o establece el tamaño de página del archivo de salida. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | Obtiene o establece los números de página que se van a editar. Por defecto, cada página sería editada. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | Obtiene o establece la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | Obtiene o establece la duración del efecto de transición. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | Obtiene o establece el estilo de transición que se usará al pasar a esta página desde otra durante una presentación. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | Obtiene o establece la alineación vertical del contenido PDF original en la página de resultados, el valor predeterminado es VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100%. El valor predeterminado es 1.0.  El siguiente ejemplo muestra cómo cambiar el zoom de las páginas del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | Aplicar los cambios realizados en las páginas del documento. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inicializa la fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Elimina Aspose.Pdf.Document enlazado con una fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | Devuelve el tamaño del cuadro especificado en el documento. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | Devuelve la rotación de la página especificada. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | Devuelve el número total de páginas. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | Devuelve el tamaño de página de la página especificada. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | Mueve el origen desde (0, 0) hasta el punto que designó. El origen está abajo a la izquierda y la unidad es el punto (1 pulgada = 72 puntos). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | Guarda el documento modificado en el flujo. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | Guarda el documento modificado en un archivo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | Persianas verticales |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | Persianas verticales |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | Barrido inferior-superior |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | Brillo diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | La página vieja se disuelve |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | Caja interior |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | Brillo de izquierda a derecha |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | Barrido de izquierda a derecha |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | Caja exterior |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | Barrido de derecha a izquierda |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | EN División horizontal |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | Fuera de división horizontal |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | En división vertical |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | División vertical hacia afuera |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | Brillo de arriba a abajo |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | Limpieza superior-inferior |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
