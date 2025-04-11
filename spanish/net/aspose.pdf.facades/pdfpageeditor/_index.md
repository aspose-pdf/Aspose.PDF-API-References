---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfPageEditor. Representa una clase para editar las páginas de archivos PDF, incluyendo rotación de página, zoom de página, movimiento de posición y cambio de tamaño de página.
type: docs
weight: 4590
url: /es/net/aspose.pdf.facades/pdfpageeditor/
---
## Clase PdfPageEditor

Representa una clase para editar las páginas de archivos PDF, incluyendo rotación de página, zoom de página, movimiento de posición y cambio de tamaño de página.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Constructor de la clase PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Constructor de la clase PdfPageEditor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Obtiene o establece la duración de visualización para las páginas. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en el que está trabajando. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal del contenido PDF original en la página de resultado, el valor predeterminado es AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Un hashtable que contiene el número de página y el grado de rotación, la clave representa el número de página, el valor de la clave representa la rotación en grados. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Obtiene o establece el tamaño de página del archivo de salida. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Obtiene o establece los números de página a editar. Por defecto, se editaría cada página. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Obtiene o establece la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Obtiene o establece la duración del efecto de transición. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Obtiene o establece el estilo de transición a utilizar al pasar a esta página desde otra durante una presentación. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Obtiene o establece la alineación vertical del contenido PDF original en la página de resultado, el valor predeterminado es VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100%. El valor predeterminado es 1.0.  El siguiente ejemplo demuestra cómo cambiar el zoom de las páginas del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Aplica los cambios realizados en las páginas del documento. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libera Aspose.Pdf.Document vinculado con una fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Devuelve el tamaño de la caja especificada en el documento. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Devuelve la rotación de la página especificada. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Devuelve el número total de páginas. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Devuelve el tamaño de la página de la página especificada. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Mueve el origen de (0, 0) al punto designado. El origen está en la parte inferior izquierda y la unidad es punto (1 pulgada = 72 puntos). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Guarda el documento cambiado en el flujo. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Guarda el documento cambiado en un archivo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Persianas Verticales |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Persianas Verticales |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Barrido de Abajo hacia Arriba |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Brillo Diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | La página antigua se disuelve |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Caja Interior |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Brillo de Izquierda a Derecha |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Barrido de Izquierda a Derecha |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Caja Exterior |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Barrido de Derecha a Izquierda |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | División Horizontal Interior |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | División Horizontal Exterior |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | División Vertical Interior |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | División Vertical Exterior |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Brillo de Arriba hacia Abajo |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Barrido de Arriba hacia Abajo |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)